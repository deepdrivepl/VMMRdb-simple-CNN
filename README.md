# VMMRdb-simple-CNN
Simple CNN model for cars' make, model and year classification on VMMRdb

Requires TF 2.0 or higher and Optuna.

For full project description please visit https://deepdrive.pl/?p=1170

## Main files
prepare_csv
 - downloads data
 - creates csv file containing labels and paths to photos
 
Finished model with data augmentation: to be added
 
## Hyperparameter optimization files
4 phrases of hyperparameter optimization:
 - optuna_conv
 - optuna_dense_make (must be adapted for model and year layers)
 - optuna_reg_make (must be adapted for model and year layers)
 - lr_scheduler
 
## Additional files
train_v1
 - just any CNN model for tests
 - single output
 - data as np.array

train_v2
 - multiple output
 - data as np.array
 
train_v3
 - single output
 - data as tf.data
 
train_v4
 - multiple output
 - data as tf.data
 
optuna_env.yml and requirements.txt - my environment's files, in case they're necessary
