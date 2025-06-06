This repo contains my solution to Pluralsight's takehome project. 

The solution is a Random Forrest classifier trained on the data in `data/recruiting_zeta-disease_training-data_take-home-challenge.csv`, with predictions made on the data in `data/recruiting_zeta-disease_prediction-data_take-home-challenge.csv`.

Predictions are saved in `predictions.csv`. Model development and data exploration are saved in `solution.ipynb`.

The trained model has an f1-score of 77% on a validation split.

Contact aaugust288@gmail.com for questions or follow-up.

Future todo:
- Save the trained model and data standardization parameters in one object (an sklearn pipeline) for convenient inference on future data.