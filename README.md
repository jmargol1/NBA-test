# NBA-test
To run the analysis for either question within the NBA portion of Projet 1, first ensure that the folder `NBA-test` is properly uploaded to the root instance of your cluster. To ensure that this folder has been downloaded properly, you can start by ensuring the following folders are contained within `NBA-test`: `NBA-test-data`, `fear_score`, and `comfort_zone`.

Next to ensure the data is in the correct place, open the directory `NBA-test/NBA-test-data/data_shot_logs.csv` and ensure that the dataset is properly placed in this location. If so you are able to continue to run the analysis for each question.

## Question 1:
To run the analysis for question 1, open the directory `NBA-test/fear_score`. This directory should include three files: `mapper.py`, `reducer.py` and `test.sh`. If all are inluded, simply run the command `bash test.sh` and let the code run. A portion of the results will be printed in the console, while the full view of the results will be in the file with directory `NBA-test/fear_score/fear_scores_final.txt`

## Question 2:
To run the analysis for question 2, open the directory `NBA-test/comfort_zone`. This directory should include the files: `mapper1.py`, `reducer1.py`, `mapper2.py`, `reducer2.py`, `mapper3.py`, `mapper4.py`, `reducer4.py`, `mapper5.py`, `reducer5.py`, `mapper6.py`, `reducer6.py`, and `test.sh`. If all are inluded, simply run the command `bash test.sh` and let the code run. After each phase, either one line of the output for many lined outputs, or the full phase output for the smaller ones will be displayed to show what each phase output looks like. At the end, the final comfort zone analyses for each of the four requested players will be printed in the console along with the interpretations of the zones. The dataset containing the best comfortable_zone for each player can be found in the file with directory `NBA-test/comfort_zone/comfort_zones_final.txt`
