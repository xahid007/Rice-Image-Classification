[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Rice Image Classification using CNN
This project focuses on classifying rice images using a Convolutional Neural Network (CNN). The CNN architecture is designed to extract relevant features from the images and make accurate predictions about different types of rice.

### **Dataset**
The dataset used in this project consists of a collection of rice images. It contains images of various rice varieties, such as Basmati, Jasmine, Arborio, and Brown rice. Each image is labeled with the corresponding rice variety for supervised training.

### **Installation**

**Clone the repository:**
git clone

**Navigate to the project directory:**
```cd rice-image-classification```

**Set up the environment:**
Ensure you have Python installed (version >= 3.6) along with pip.

**Install the required packages by running:**
``` pip install -r requirements.txt```


### **Usage**
**Prepare the dataset:**
* Place the rice images in the appropriate directory structure.
* The images should be organized into separate folders, with each folder representing a different rice variety.

**Data Preprocessing:**
* Modify the file paths in the code to match your dataset location.
* Execute the code to perform data preprocessing, which includes reading the images, creating a DataFrame, and visualizing the images.

**Splitting the Dataset:**
* The dataset is split into train, validation, and test sets using the **_splitfolders_** library.
* Run the code to split the dataset into the desired proportions.

**Model Training:**
* Set the appropriate parameters for the data generators, such as batch size, image size, etc.
* Run the code to train the CNN model on the training dataset.

**Model Evaluation:**
* Evaluate the trained model on the test dataset to measure its performance.
* Run the code to obtain evaluation metrics such as accuracy, loss, etc.

**Predictions:**
* Use the trained model to make predictions on new rice images.
* Modify the code to specify the location of the images to be predicted.
* Run the code to obtain the predicted labels for the input images.

### **Model Architecture**
The CNN model used for rice image classification consists of the following layers:
* **Convolutional layers:** These layers perform feature extraction by applying filters to the input images.
* **MaxPooling layers:** These layers reduce the spatial dimensions of the feature maps generated by the convolutional layers.
* **Flatten layer:** This layer converts the multi-dimensional feature maps into a 1D vector.
* **Dense layers:** Fully connected layers that learn to classify the input based on the extracted features.
* **Activation functions:** The ReLU activation function is used in the convolutional and dense layers, except for the output layer, which uses the softmax activation function to produce the class probabilities.

### **Acknowledgments**
The dataset used in this project was sourced from [MURAT KOKLU](https://www.muratkoklu.com/datasets/).

### **License**
This project is licensed under the MIT License.

