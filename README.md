# CS5720 Neural Networks and Deep Learning - Home Assignment 2
**University of Central Missouri**  
**Department of Computer Science & Cybersecurity**  
**Spring 2025**  
**Student Name:** Akhil Dondapati 
**Student ID:** 700756446 

---

## Question 1: Cloud Computing for Deep Learning
- **Description**: This section provides written definitions of elasticity and scalability in the context of cloud computing for deep learning, along with a comparison of AWS SageMaker, Google Vertex AI, and Microsoft Azure Machine Learning Studio. No code is required for this question; the answers are documented directly in the assignment submission.
- **Files**: No code files; answers are in the report/video.

---

## Question 2: Convolution Operations with Different Parameters
- **File**: `question2_convolution.py`
- **Description**: This script uses TensorFlow and NumPy to perform convolution operations on a 5×5 input matrix with a 3×3 kernel. It computes feature maps for four cases: stride=1 with 'VALID' padding, stride=1 with 'SAME' padding, stride=2 with 'VALID' padding, and stride=2 with 'SAME' padding. The output feature maps are printed for each case, demonstrating how stride and padding affect convolution results.
- **Key Features**: Custom input matrix and kernel, dynamic convolution using `Conv2D`, and clear output formatting.

---

## Question 3: CNN Feature Extraction with Filters and Pooling
### Task 1: Edge Detection Using Convolution
- **File**: `question3_task1_edge_detection.py`
- **Description**: This script applies edge detection to a grayscale image using Sobel filters with OpenCV and NumPy. It loads an image (or generates a dummy one if none is provided), applies Sobel-X and Sobel-Y filters to detect edges in horizontal and vertical directions, and displays the original and filtered images side-by-side using Matplotlib.
- **Key Features**: Sobel filter implementation, image visualization, and fallback dummy image generation.

### Task 2: Max Pooling and Average Pooling
- **File**: `question3_task2_pooling.py`
- **Description**: This script demonstrates max pooling and average pooling on a random 4×4 matrix using TensorFlow/Keras. It creates a sample input matrix, applies 2×2 max pooling and average pooling with stride=2, and prints the original, max-pooled, and average-pooled matrices to show the effects of each operation.
- **Key Features**: Random matrix generation, pooling layer application, and result comparison.

---

## Question 4: Implementing and Comparing CNN Architectures
### Task 1: Implement AlexNet Architecture
- **File**: `question4_task1_alexnet.py`
- **Description**: This script implements a simplified AlexNet model using TensorFlow/Keras. It defines a sequential model with convolutional layers (starting with 96 filters), max pooling layers, fully connected layers (4096 neurons), dropout for regularization, and a softmax output layer for 10 classes. The model summary is printed to display its architecture and parameters.
- **Key Features**: Faithful recreation of AlexNet structure, layer configuration, and summary output.

### Task 2: Implement a Residual Block and ResNet
- **File**: `question4_task2_resnet.py`
- **Description**: This script defines a residual block function and builds a ResNet-like model using TensorFlow/Keras. The residual block includes two convolutional layers with skip connections, and the model starts with a 7×7 convolution, followed by two residual blocks, a flatten layer, a dense layer (128 neurons), and a softmax output layer. The model summary is printed to show its structure.
- **Key Features**: Custom residual block, skip connection implementation, and ResNet architecture.

---
