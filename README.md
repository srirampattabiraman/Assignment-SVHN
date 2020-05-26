# Assignment-SVHN
Approach to classify SVHN format 1 dataset

Below are the approach to classify the annotated SVHN

1. Serialize annotated input images via tfrecords through the script convert_to_tfrecords.py
2. Designing a model through model.py script that has 
  10 hidden layers.
  logits for maximum 5 digits.
  sparse categorical entropy loss function
3. Train and evaluate the model through train.py script via tensorflow framework.
  
