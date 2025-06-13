# Group 43 Repo

This repository contains our group's (Group 43) submission in the CSE 151B Spring 2025 Competition https://www.kaggle.com/competitions/cse151b-spring2025-competition/.

### Data Exploration
EDA is contained entirely within the `my-data-exploration.ipynb` file.

### Baseline Model and Final Model
Model architecture and training/evaluation pipeline are all present in `final-notebook.ipynb`. The main focus of our paper is on `SimpleCNN`, which we used as a baseline, and the `TemporalHierarchicalTransformerPlus`, which is our final model. The other model architectures in the notebook are all intermediary models that we tried out (mainly variations of the Transformer architecture).

### Model Weights
`best-final-score-37-0.8018.ckpt` and `best-final-score-53-0.7920.ckpt` are our saved final models. They actually refer to the same model on the same training run, but just saved at different epochs (37 and 53, the ones with the lowest validation loss). These two similar model weights were used in our chosen 2 final Kaggle submissions. `best-final-score-53-0.7920.ckpt` performed just as our validation metric predicted, at around 0.79 on the private leaderboard. 
