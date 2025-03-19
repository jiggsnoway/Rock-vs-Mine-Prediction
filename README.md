# Sonar Rock vs. Mine Prediction

A machine learning model using **Logistic Regression** to classify sonar signals as either **Rock (R)** or **Mine (M)**.

## 📂 Dataset Information
- The dataset contains **60 numerical features** representing sonar signal frequencies.
- The last column (label) contains **"R" for Rock** and **"M" for Mine**.
- Source: https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/view

## 🛠 Installation & Setup

1. Clone this repository:
   ```sh
   git clone https://github.com/jiggsnoway/sonar-rock-mine-prediction.git
   ```
2. Navigate to the project folder:
   ```sh
   cd sonar-rock-mine-prediction
   ```
3. Install required dependencies:
   ```sh
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
4. Open and run the **Google Colab Notebook** [Click here](https://colab.research.google.com/)

## 🎯 Model & Approach
- **Algorithm Used:** Logistic Regression
- **Accuracy Achieved:** 83%

### 🔹 Steps:
1. Load and explore the dataset.
2. Preprocess the data (handling missing values, feature scaling).
3. Split into **training (80%) and testing (20%)** sets.
4. Train the **Logistic Regression** model.
5. Evaluate using a **Confusion Matrix & Accuracy Score**.


## 🚀 How to Use?
To make predictions:
```python
input_data = [0.0071,	0.0103,	0.0135,	0.0494,	0.0253,	0.0806,	0.0701,	0.0738,	0.0117,	0.0898,	0.0289,	0.1554,	0.1437,	0.1035,	0.1424,	0.1227,	0.0892,	0.2047,	0.0827,	0.1524,	0.3031,	0.1608,	0.0667,	0.1426,	0.0395,	0.1653,	0.3399,	0.4855,	0.5206,	0.5508,	0.6102,	0.5989,	0.6764,	0.8897,	1,	0.9517,	0.8459,	0.7073,	0.6697,	0.6326,	0.5102,	0.4161,	0.2816,	0.1705,	0.1421,	0.0971,	0.0879,	0.0863,	0.0355,	0.0233,	0.0252,	0.0043,	0.0048,	0.0076,	0.0124,	0.0105,	0.0054,	0.0032,	0.0073,	0.0063] 
prediction = model.predict([input_data])
print(prediction)
```

## 👤 Author
- **Jigyashman Hazarika**
- 📧 Email: jiggsnoway18@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/jigyashmanhazarika)

## 📜 License
This project is licensed under the MIT License.
