# Bank Marketing Prediction Project

This repository contains a machine learning project to predict client subscription to a term deposit using the Bank Marketing dataset.

## Project Overview
The project compares two models:
- **Neural Network**
- **Random Forest Classifier**

Both models are evaluated based on their ability to classify whether a client subscribes to a term deposit.

## Dataset
The dataset used is `bank-additional-full.csv`, which includes:
- Client attributes (e.g., age, job, marital status)
- Campaign details (e.g., contact duration, number of previous contacts)
- Target variable: `y` (indicating subscription: "yes" or "no")

## Requirements
Install the required libraries using:
```bash
pip install -r requirements.txt
```

## Steps to Run
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd bank-marketing-prediction
   ```
3. Place the dataset file (`bank-additional-full.csv`) in the root directory.
4. Run the main script:
   ```bash
   python main.py
   ```

## Features
- **Data Preprocessing**: Handles categorical encoding and feature scaling.
- **Model Training**: Trains a neural network and a random forest classifier.
- **Evaluation**: Provides metrics such as accuracy, precision, recall, and F1-score.
- **Testing Interface**: Allows interactive testing with specific or random samples.

## Output
- Trained model files:
  - `neural_network_model.keras`
  - `random_forest_model.pkl`
- Performance metrics and confusion matrices for both models.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
