# Hate Speech Recognition Project

Welcome to the Hate Speech Recognition Project repository. This project aims to develop and evaluate models for detecting hate speech using different machine learning frameworks and techniques. Below is a description of the key files included in this repository:

## Files Overview

### 1. `hate_speech_recognition_tf.ipynb`
This Jupyter Notebook contains the implementation of the **first strategy** using TensorFlow. In this implementation:
- The model architecture is based on the Transformer model.
- Only the final layer of the Transformer model is fine-tuned during training.
- This notebook focuses on leveraging TensorFlow for hate speech detection.

### 2. `hate_speech_recognition_pytorch.ipynb`
This Jupyter Notebook contains the implementation of the **second strategy** using PyTorch. In this implementation:
- The model architecture is also based on the Transformer model.
- It utilizes PyTorch's framework to train and evaluate the model.
- This notebook provides an alternative approach to hate speech recognition using PyTorch.

### 3. `hate_speech_recognition_eda_preprocess.ipynb`
This Jupyter Notebook includes:
- **Exploratory Data Analysis (EDA)**: Identifies and explores the dataset to understand its structure and contents.
- **Preprocessing**: Applies various preprocessing steps to the dataset to prepare it for model training.
- **Dataset Splitting**: Splits the dataset into training, validation, and test sets.
- **File Saving**: Saves the preprocessed datasets into CSV files for further use in model training and evaluation.

## Getting Started

1. **Setup**: Ensure you have the required dependencies installed. For TensorFlow and PyTorch, you can follow their respective installation guides.
2. **Data**: Make sure to have the dataset available and appropriately configured for the notebooks to read.
3. **Running Notebooks**: Open and run the Jupyter Notebooks in the order listed above to understand and experiment with the hate speech recognition models.

## Contributing

Feel free to fork this repository and submit pull requests if you have improvements or additional features to propose. Please ensure that your contributions adhere to the project's code style and include appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or comments, please open an issue or contact the project maintainers.

