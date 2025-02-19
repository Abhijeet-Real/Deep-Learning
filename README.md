# MNIST Digit Classification Project

## Overview
This project implements a deep learning model to classify handwritten digits from the MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images of digits (0-9). The model is trained using TensorFlow and Keras.

## Features
- Uses Convolutional Neural Networks (CNNs) for high accuracy.
- Implements data augmentation to improve generalization.
- Includes visualization of training history and confusion matrix.
- Includes a Jupyter Notebook (`mnist.ipynb`) for step-by-step experimentation.
- Contains a custom-written collection of images for additional testing.
- Uses a `requirements.txt` file for easy dependency management.
- Works with the MNIST dataset stored in the `data/` folder.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- OpenCV

### Setup
Clone the repository and install dependencies:
```bash
# Clone the repository
git clone https://github.com/Abhijeet-Real/Deep-Learning.git
cd mnist-project

# Install dependencies
pip install -r requirements.txt
```

## Usage
### Training the Model
To train the CNN model, run:
```bash
python train.py
```
This will save the trained model as `mnist_model.h5`.

### Testing the Model
Run the following command to evaluate the model:
```bash
python test.py
```

### Using the Jupyter Notebook
For an interactive step-by-step analysis, open the notebook:
```bash
jupyter notebook mnist.ipynb
```

## Project Structure
```
mnist-project/
│──.gitignore         #Gitignore
│── mnist.ipynb       # Main Jupyter Notebook for analysis
│── README.md         # Project documentation
```

## Results
- Achieved **98%+ accuracy** on the test set.
- Model generalizes well to unseen handwritten digits.
- Additional custom images allow for extended model evaluation.

## Future Improvements
- Implement hyperparameter tuning.
- Deploy as a web API using Flask or FastAPI.
- Extend to recognize letters (A-Z) using the EMNIST dataset.

## License
This project is licensed under the MIT License.

## Author
Abhijeet
Abhijeet1472@gmail.com
https://github.com/Abhijeet-Real