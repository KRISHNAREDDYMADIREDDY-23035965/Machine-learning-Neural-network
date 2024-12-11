# Convolutional Neural Networks (CNN) Tutorial

This repository contains a tutorial on **Convolutional Neural Networks (CNNs)**, including code implementation and guidance on training a CNN model for image classification tasks. The tutorial uses the **Cats vs. Dogs Dataset** to demonstrate the concepts.

## Dataset

The **Microsoft Cats vs. Dogs Dataset** is used for training and testing the CNN model. Due to its large size, the dataset is not included in this repository. You can download the dataset programmatically using the provided code snippet below, either locally or in Google Colab.

### Access the Dataset
Use the following code snippet to download the dataset:
```python
import kagglehub

# Download the dataset
path = kagglehub.dataset_download("shaunthesheep/microsoft-catsvsdogs-dataset")

print("Path to dataset files:", path)
```

## Using Google Colab to Run the Tutorial

The tutorial is hosted on **Google Colab**, providing a convenient platform to run the code without any local setup. This environment allows you to execute the code seamlessly, visualize results, and experiment with the model.

You can access and run the tutorial using the following link:

[Google Colab Tutorial](https://colab.research.google.com/drive/1KGd0MFtksCboCY-QAIrKToAC__5_5dcQ?usp=sharing)

Follow the step-by-step instructions in the Colab notebook to download the dataset, train the CNN model, and evaluate its performance.
