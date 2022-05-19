# AWS_SageMaker_TensorFlow_Keras_CNN_Model_Fashion_MNIST

<h3><b><u>Introduction:</u></b></h3>

This project covers the end to end implementation of a Convolutional Neural Network (CNN) Multi-Class Classifier Deep Learning Model for the Fashion MNIST Dataset using TensorFlow Keras and Apache MXNet on the GPU Instance using AWS SageMager.

AWS SageMaker is a fully-managed cloud based service offered by AWS to build, design and deploy E2E machine learning models.

The objective of the Deep Learning model is to predict and classify the fashion images in to various classes/categories using the deep learning techniques of TensorFlow Keras and Apache MXNet.

<h3><b><u>Dataset:</u></b></h3>

Link to the Kaggle Dataset as below:
<h4><a href="https://www.kaggle.com/datasets/zalando-research/fashionmnist" style="color: blue"><b><u>Fashion MNIST Dataset</u></b></a></h4>

Dataset Context, Content and Labels Information as per Kaggle as below:

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Zalando seeks to replace the original MNIST dataset.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

Each training and test example is assigned to one of the following labels:

0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot

<h3><b><u>Project Implementation Steps using AWS SageMaker:</u></b></h3>

1. Data Ingestion into AWS S3 Bucket
2. Data Collection and Data Retrieval from AWS S3 Bucket into AWS SageMaker
3. Data Exploration and Analysis
4. Data Pre-processing, Scaling and Normalisation
5. Model Training
6. Model Evaluation and Validation
7. Configured Automatic Model Tuning
8. Model Performance Metrics Measures
9. Deploying the Finalized Best Model into AWS
10. Generating the Inference Endpoint for the Finalized Model
11. Verifying the EndPoint with Unseen Test Data

<h3><b><u>Tools & Technologies:</u></b></h3>

Python, CNN, TensorFlow, Keras, Apache MXNet, AWS IAM, AWS S3, AWS SageMaker


