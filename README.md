## Run on Kaggle

This notebook can be run directly on Kaggle.

### Notes

- Batch size may need to be adjusted based on available GPU memory.
- In this implementation:
  - `per_device_train_batch_size = 24`
  - `submission_test(..., batch_size=75)`
- The current settings are tuned for an A100 GPU.
