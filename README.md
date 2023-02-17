# mechinelerning
Animal Diet Classification Model
This is a machine learning model that classifies animals into herbivores or carnivores based on their names.

Requirements
Python 3
Keras
Usage
Clone the repository to your local machine
Open the animal_classification.ipynb notebook in Jupyter Notebook or Jupyter Lab
Run the code cells in the notebook to train and test the model
Data
The texts variable in the code contains a list of animal names that are used as input data. The labels variable contains the corresponding labels for each animal (0 for herbivores and 1 for carnivores).

Model Architecture
The model uses an embedding layer followed by a dense layer with a ReLU activation function and a final output layer with a sigmoid activation function. The model is compiled using the Adam optimizer and binary cross-entropy loss.

Results
The model achieves a test accuracy of approximately 80%.

Contributors
Your Name Here
License
This project is licensed under the MIT License - see the LICENSE file for details
