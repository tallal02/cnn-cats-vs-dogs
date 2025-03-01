# CNN Cats vs Dogs Project

This project demonstrates a hands-on approach to building and evaluating a Convolutional Neural Network (CNN) for classifying images from the Microsoft Cats vs Dogs dataset. The focus is on understanding the inner workings of CNNs through practical implementation, training, and analysis.

## Objectives

- **Dataset Preparation:**  
  Download and preprocess a subset of the Microsoft Cats vs Dogs dataset. In this example, you will work with a dataset containing 6,000 images of cats and 6,000 images of dogs, organized in separate folders.  
  **Dataset Link:** Download the dataset from Kaggle at [Microsoft Cats vs Dogs on Kaggle](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset).

- **CNN Model Development:**  
  Create a CNN using convolutional, activation, pooling, and fully connected layers to perform image classification.

- **Training and Evaluation:**  
  Train the model and assess its performance using:
  - Confusion Matrix
  - Accuracy
  - Precision & Recall
  - AUC-ROC

  During training, the CNN model was run for 40 epochs on the Cats vs Dogs dataset with a training-validation split. The training log below shows key metrics—accuracy, loss, and learning rate—     recorded at each epoch:

  ```plaintext
  Epoch 1/40
  300/300 ━━━━━━━━━━━━━━━━━━━━ 76s 251ms/step - accuracy: 0.5869 - loss: 0.9320 - val_accuracy: 0.5183 - val_loss: 0.7521 - learning_rate: 0.0010
  Epoch 2/40
  300/300 ━━━━━━━━━━━━━━━━━━━━ 6s 18ms/step - accuracy: 0.6875 - loss: 0.7691 - val_accuracy: 0.5138 - val_loss: 0.7575 - learning_rate: 0.0010
  ...
  Epoch 40/40
    1/300 ━━━━━━━━━━━━━━━━━━━━ 1:08 229ms/step - accuracy: 0.9688 - loss: 0.1249 - val_accuracy: 0.9042 - val_loss: 0.2208 - learning_rate: 6.2500e-05
  Restoring model weights from the end of the best epoch: 37.
  '''

- **Visualization and Analysis:**  
  Visualize sample images along with training and testing error/accuracy curves. Evaluate various performance metrics to gain insights into the model's behavior.

## Clone the Repository

Clone the repository to get started:

```bash
git clone https://github.com/tallal02/cnn-cats-vs-dogs-assignment.git
cd cnn-cats-vs-dogs-assignment
