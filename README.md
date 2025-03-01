# CNN Cats vs Dogs Project

This project demonstrates a hands-on approach to building and evaluating a Convolutional Neural Network (CNN) for classifying images from the Microsoft Cats vs Dogs dataset. The focus is on understanding the inner workings of CNNs through practical implementation, training, and analysis.

## Objectives

- **Dataset Preparation:**  
  Download and preprocess a subset of the Microsoft Cats vs Dogs dataset. In this example, you will work with a dataset containing 6,000 images of cats and 6,000 images of dogs, organized in separate folders.

- **CNN Model Development:**  
  Create a CNN using convolutional, activation, pooling, and fully connected layers to perform image classification.

- **Training and Evaluation:**  
  Train the model and assess its performance using:
  - Confusion Matrix
  - Accuracy
  - Precision & Recall
  - AUC-ROC

- **Visualization and Analysis:**  
  Visualize sample images along with training and testing error/accuracy curves. Evaluate various performance metrics to gain insights into the model's behavior.

## Project Structure

```
├── data/                   # Contains the dataset folders (cats/ and dogs/) with 6000 images each
├── notebooks/              # Jupyter notebooks for exploration and visualization
├── src/                    # Source code for model definition, training, and evaluation
│   ├── model.py            # CNN model architecture
│   ├── train.py            # Script for training the model
│   └── evaluate.py         # Script for model evaluation
├── README.md               # This file
└── requirements.txt        # List of required Python packages
```

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/cnn-cats-vs-dogs-assignment.git
   cd cnn-cats-vs-dogs-assignment
   ```

2. **Set Up a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare the Data:**  
   Ensure the `data/` folder contains the two subdirectories `cats/` and `dogs/`, each with 6000 images. Follow any additional preprocessing instructions in the `data/` folder if needed.

2. **Train the Model:**  
   Run the training script:

   ```bash
   python src/train.py
   ```

3. **Evaluate the Model:**  
   Execute the evaluation script:

   ```bash
   python src/evaluate.py
   ```

4. **Explore Visualizations:**  
   Open the Jupyter notebooks in the `notebooks/` directory to view detailed visualizations of training and testing metrics, as well as the model's performance analysis.

## Results

The project includes:
- Visual examples from the dataset
- Plots for training and testing errors/accuracies
- Evaluation results featuring a confusion matrix, precision, recall, and AUC-ROC analysis

## Contributing

Contributions, suggestions, and improvements are welcome. Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
