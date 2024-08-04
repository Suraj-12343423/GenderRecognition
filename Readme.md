# Gender Recognition Using CNNs

## Project Overview
This project aims to build a Convolutional Neural Network (CNN) to classify gender based on facial images. The model is trained and evaluated on a dataset of labeled images, achieving competitive accuracy through various data augmentation and regularization techniques.

## Dataset
The dataset used for this project is the [Gender Recognition Dataset](https://www.kaggle.com/datasets/divanshu22/gender-recognition-dataset). It contains images of male and female faces which are divided into training and validation sets.

### Dataset Structure
- `Train/`
  - `Male/`
  - `Female/`
- `Validation/`
  - `Male/`
  - `Female/`

## Model Architecture
The model is built using the TensorFlow and Keras libraries. The architecture consists of:
- Three convolutional layers with ReLU activation and max pooling.
- A flattening layer to convert the 2D matrix to a vector.
- Two dense layers, including a dropout layer for regularization.
- A final dense layer with a sigmoid activation function for binary classification.
```

## Results
The model's performance is evaluated on the validation set. Here are some key metrics:
- **Accuracy**: Achieved ~97% accuracy on the validation set.
- **Loss**: Binary cross-entropy loss was used.



## Conclusion
This project demonstrates how CNNs can be used for image-based gender recognition. The trained model achieves an accuracy of 97% and can be further improved by using more advanced architectures and larger datasets.

## Future Work
- Explore more complex architectures like ResNet or Inception.
- Implement data augmentation techniques to improve model generalization.
- Deploy the model as a web application using Flask or Streamlit.

## Acknowledgments
- [Kaggle](https://www.kaggle.com/) for providing the dataset.

