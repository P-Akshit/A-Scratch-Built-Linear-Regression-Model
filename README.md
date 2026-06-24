# Linear Regression from Scratch: Predicting Student Marks 📈

**Academic Context: BCA 1st Year, 2nd Semester Project**

A purely from-scratch Python implementation of a Single Variable Linear Regression model. Instead of relying on pre-built machine learning libraries like `scikit-learn`, this project builds the mathematical engine—including the Cost Function (MSE) and Gradient Descent algorithm—entirely from the ground up to demonstrate a foundational understanding of Artificial Intelligence mechanics.

## 📊 Data Collection
The dataset used to train this model (`AvgStudyHour.xlsx` and `Marks.xlsx`) was independently collected using Google Forms. It consists of mostly real, custom-gathered data rather than standard, pre-cleaned tutorial datasets, demonstrating end-to-end data pipeline handling from collection to prediction.

## ✨ Features
* **Custom Mathematical Engine:** Manual implementation of Gradient Descent and Mean Squared Error algorithms.
* **Real-World Data Handling:** Reads training data directly from Excel files using Pandas.
* **Interactive Predictor:** Includes a command-line interface for users to input custom study hours and instantly receive a predicted exam score.
* **Visualized Data:** Uses Matplotlib to plot the raw scatter data and overlay the final trained line of best fit.
* **Heavily Documented:** Every line of the script includes detailed comments explaining the underlying mathematics, logic, and machine learning principles.

## 🛠️ Dependencies
Ensure you have the following Python libraries installed before running the script:
* `numpy`
* `pandas`
* `matplotlib`
* `openpyxl` *(Required by pandas to read the .xlsx files)*

You can install these via pip:
`pip install numpy pandas matplotlib openpyxl`

## 🚀 Usage
1. Clone this repository to your local machine.
2. Ensure the data files (`AvgStudyHour.xlsx` and `Marks.xlsx`) are located in the same directory as the Python script.
3. Run the script.
4. The model will train over 2000 epochs, display the plotted data, and prompt you to enter a target study hour value in the terminal to predict the final mark.

## 📜 License
This project is open-source and intended for educational purposes. **Copyrighted for non-commercial use only.** You may reuse, modify, and distribute this code strictly for open-source projects. It may not be used for any commercial sales or for-profit operations.

## 👨‍💻 Author
**Akshit Pandey**
