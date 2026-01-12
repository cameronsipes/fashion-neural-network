How to run this project:

1. Open terminal and go to the folder where fashion.ipynb, requirements.txt, and the folder called data are located.
2. Create Python virtual environment: python -m venv .venv
3. Activate Virtual Environment: .\.venv\Scripts\activate
3. Download pip to virtual environment: python -m pip install --upgrade pip
4. Download dependencies to virtual environment: python -m pip install -r requirements.txt
5. For VSCode click "Select Kernel", then "Python Environments...", then "+ Create Python Environment", then "Enter Interpreter Path...", then ".venv", then "Scripts", then "python".
6. Simply select "Run All".

What this project is:

This project was for CS 307 Modeling and Machine Learning in Data Science at UIUC. This project builds a neural network that classifies images of clothing using the Fashion-MNIST dataset. Fashion-MNIST contains grayscale images of apparel items such as shirts, shoes, bags, and coats, with each image belonging to one of 10 categories.

The notebook loads the image data using TorchVision, converts the images into tensors, and batches the data for training. It then trains a PyTorch convolutional neural network, a type of model commonly used for image classification tasks.

The model is trained on 60,000 training images and evaluated on a separate test set of 10,000 images. In the most recent run, found at the bottom of fashion.ipynb, the model achieved a final test accuracy of 0.9243 or 92.43%. This means the model correctly classified roughly 92 out of every 100 test images it had not seen during training.