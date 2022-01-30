### Transformation operations can happen at the instance level or be applied to the entire dataset. Which one is an instance-level transformation?
* Feature Cross

### In a pre-processing training dataset, all transformations that are carried out must be done in the serving set:
True. Also, this is considered a con, as it can produce slower iterations being less efficient than in the training.

### What statement is true about TensorFlow Transform?
* TF Transform eliminates the risk of introducing training-serving skew. TF Transform uses the same code path for both training and serving.