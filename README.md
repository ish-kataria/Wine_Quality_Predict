
# Wine Quality Prediction

This repository provides a machine learning solution for predicting wine quality based on various chemical properties. The dataset used comes from the UCI Machine Learning Repository, specifically the **Wine Quality Dataset**, which includes red and white wine samples.

---

## Overview

Wine quality prediction can assist winemakers in identifying the characteristics that contribute to a high-quality wine. This project demonstrates the full machine learning pipeline, from data preprocessing to model training and evaluation.

---

## Features

- **Dataset:** 
  - The dataset contains physicochemical features (e.g., acidity, sugar, pH) and a quality score rated by wine tasters.
  - Download from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).
- **Machine Learning Models Implemented:**
  - Logistic Regression
  - Stochastic Gradient Descent Classifier
  - Random Forest
  - Support Vector Machine (SVM)
  - Decision Tree
  - Artificial Neural Networks
- **Data Preprocessing:**
  - Handles missing values, outliers, and scales features appropriately.
- **Evaluation Metrics:**
  - Accuracy, Confusion Matrix
  - Precision, Recall, F1-score

---

### Clone the Repository

Clone this repository to your local environment:

```bash
git clone https://github.com/ish-kataria/Wine_Quality_Predict
cd Wine-Quality-Prediction
```

---

## Usage

1. **Prepare the Dataset:**
   - Ensure the dataset (`winequality-red.csv`, `winequality-white.csv`) is present in the source directory.
   - Alternatively, download and place the dataset manually.

2. **Run the Notebook:**
   Execute the notebook in google colab to preprocess the data, train models, and display results:

3. **Results:**
   - Displays evaluation metrics in the console.
   - Saves performance visualizations and comparison graphs.

---

## Project Structure

```
Wine-Quality-Prediction/
├── .csv file           # dataset
├── .ipynb file         # Google Colab Notebook
├── README.md           # Project documentation (this file)
```

---

## Example Output

- **Feature Correlation Heatmap**  
  <img width="786" alt="Screenshot 2024-11-30 at 4 02 52 PM" src="https://github.com/user-attachments/assets/064eefaf-d18c-47ba-9563-fccc52b5f30c">


- **Model Performance Comparison**  
  ```
  Logistic Regression: 74.49% Accuracy
  Stochastic Gradient Descent: 66.84% Accuracy
  SVM: 75.14% Accuracy
  Random Forest: 81.30 % Accuracy
  Decision Tree: 77.54 % Accuracy
  Multi Layer Perceptron: 70.27 % Accuracy
  Artificial Neural Networks: 71.52 % Accuracy
  ```

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Wine Quality Dataset provided by the UCI Machine Learning Repository.
- Inspiration from scikit-learn's machine learning examples.

---
