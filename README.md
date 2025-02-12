🚑 Disease Prediction Using Machine Learning

📌 Overview

This project is a machine learning-based disease prediction system that analyzes user-input symptoms and predicts the most probable disease. It leverages a trained model and a structured dataset to assist in early diagnosis and healthcare decision-making.

🏥 Features

Predicts diseases based on symptoms entered by the user

Uses a pre-trained machine learning model

Processes user inputs efficiently in a structured format

Provides a data-driven approach for early diagnosis

📂 Dataset

The project uses the symbipredict_2022.csv dataset, which contains various symptoms mapped to their respective diseases. The model is trained to recognize patterns in symptom occurrence.

🚀 How It Works

User Input: The user enters symptoms separated by commas.

Data Processing: The symptoms are converted into a binary format, matching the dataset structure.

Prediction: The trained model analyzes the input and predicts the most likely disease.

Output: The predicted disease is displayed to the user.

🛠 Tech Stack

Python 🐍 (Pandas, NumPy, Scikit-Learn, Joblib)

Machine Learning 🤖 (Supervised Learning Model)

🔧 Setup & Installation

Clone the repository:

git clone https://github.com/RKRanjithkumarRK/Health-Scan/tree/main

Navigate to the project directory:

cd disease-prediction

Install dependencies:

pip install pandas numpy scikit-learn joblib

Run the script:

python predict.py

🏆 Example Usage

Enter symptoms separated by commas: fever, cough, headache
Predicted Disease: Flu

📌 Future Enhancements

Deploying as a web application

Adding more symptoms and diseases for better accuracy

Integrating with real-time medical databases

🤝 Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome! 😊

📜 License

This project is licensed under the MIT License.
