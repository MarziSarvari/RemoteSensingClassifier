# Remote Sensing Image Classification using Convolutional Neural Networks
## Overview

This repository contains the code for a convolutional neural network (CNN) based approach for classifying components in remote sensing images. The code is implemented in Python using the Keras deep learning library and is designed to classify components such as buildings, cars, grass, pavement, etc., in remote sensing images.

## Requirements

- Python 3.x
- Keras
- numpy
- scikit-learn
- tifffile
- skimage
- matplotlib
- Pillow

You can install the required Python packages using pip:

```
pip install -r requirements.txt
```

## Usage
Clone the repository: 
```
git clone https://github.com/MarziSarvari/RemoteSensingClassifier.git
```

2. Navigate to the project directory:


3. Prepare your dataset:

   - The dataset should be organized in the following structure:
   

```
├── data
│   ├── UCMerced
│   │   ├── images
│   │   │   ├── image1.tif
│   │   │   ├── image2.tif
│   │   │   └── ...
│   │   └── multilabels.txt
├── prediction
│   ├── pred1.png
│   ├── pred2.png
|   └── ...
```

4. Preprocess the data:

   - Ensure that your dataset is prepared and organized correctly.
   - Update the `data_path` variable in the code to point to the location of your dataset.
   - Run the data preprocessing code to resize and normalize the images.

5. Train the model:

   - Run the main script to train the CNN model on the preprocessed dataset.

6. Evaluate the model:

   - Evaluate the trained model on a test set to assess its performance.

7. Make predictions:

   - Use the trained model to make predictions on new images.
