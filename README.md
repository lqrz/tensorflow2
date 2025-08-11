# Tensorflow2

A learning-focused collection of TensorFlow 2 / Keras Jupyter notebooks.

## Concepts Covered

This repository demonstrates several core **TensorFlow 2 / Keras** concepts through practical Jupyter notebooks:

1. **Model Regularisation**  
   - L1, L2, and combined L1/L2 weight penalties (`kernel_regularizer` in `Dense` layers).  
   - Dropout layers and their effect on overfitting.  
   - Understanding the bias–variance trade-off.

2. **Batch Normalisation**  
   - Using `tf.keras.layers.BatchNormalization`.  
   - Effects on training dynamics and stability.  
   - Best practices for placing batch norm in the architecture (before/after activation).

3. **Weight Initialisation**  
   - Built-in initializers like `RandomNormal`, `HeNormal`, `GlorotUniform`, etc.  
   - How different initializers impact convergence speed and gradient flow.

4. **Validation Strategies**  
   - Splitting training/validation sets using `validation_split` in `.fit`.  
   - Leveraging validation metrics for model improvement.  
   - Avoiding data leakage between training and validation sets.

5. **Callbacks**  
   - `EarlyStopping` to halt training when validation loss stops improving.  
   - Other useful callbacks such as `ModelCheckpoint` (examples in the `callbacks/` folder).  
   - Logging and monitoring training via callbacks.

6. **Saving and Loading Models**  
   - Saving in **SavedModel** format (`model.save`, `tf.keras.models.load_model`).  
   - Saving/loading with HDF5 (`.h5`) format.  
   - Partial weight loading for transfer learning and fine-tuning.

---

