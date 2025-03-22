# CNN-Dog-Cat-Classifier

This project classifies images into two categories: **Dog** or **Cat**, based on a **Convolutional Neural Network (CNN)** built with **PyTorch**.

### Dataset
The dataset used is the **Microsoft Cats vs. Dogs Dataset** from Kaggle:
[Download here](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset).

### Model Architecture
The model is a simple **CNN** with the following structure:
- **2 convolutional layers**
- **2 pooling layers** (Max Pooling)
- **2 fully connected layers** (to map pooled features to the final output).

### Instructions:
1. Download the **dataset** from kaggle and unzip it.
2. Specify the path to the dataset in `path_to_dataset` in the code.
3. Run the model by simply executing the code below.
