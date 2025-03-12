# Digital-recognition
Tech Stack Used:
------------------------------------------------
Python: Main programming language
PyTorch: Deep learning framework
Torchvision: Handles MNIST dataset loading and transformations
Matplotlib: For visualizing images
NumPy: Basic array manipulations

Project Structure:
------------------------------------------------
Data Loading & Preprocessing: MNIST dataset is downloaded, normalized, and loaded using DataLoader.
Model Architecture: A simple 3-layer feedforward neural network with ReLU activation.
Training: Uses CrossEntropyLoss and Adam optimizer to minimize error over 5 epochs.
Evaluation: Computes model accuracy on test data.
Prediction on Single Image: Tests the model on a random image from the dataset and displays the predicted digit.

Results:
--------------------------------------------------
Expected accuracy: Above 90% on the test dataset.
The model can correctly classify most digits.
