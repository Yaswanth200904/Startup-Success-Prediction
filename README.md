🚀 Prosperity Prognosticator – Startup Success Prediction
📌 Project Overview

Prosperity Prognosticator is a machine learning web application that predicts whether a startup will be Acquired or Closed based on key business and funding parameters.
The model is trained using the Kaggle Startup Success Prediction dataset and deployed using Flask.

🎯 Objective

To build a data-driven system that helps:

Investors evaluate startup potential

Entrepreneurs plan strategies

Reduce financial risk in decision making

🧠 Machine Learning Model

Algorithm: Random Forest Classifier

Accuracy: 84%

Validation Method: 80-20 Train-Test Split

📊 Input Features

The model takes the following inputs:

funding_total_usd

funding_rounds

age_first_funding_year

age_last_funding_year

age_first_milestone_year

age_last_milestone_year

relationships

📈 Output

The system predicts:

✅ Startup will be Acquired
❌ Startup may be Closed
📊 With success probability score

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Flask

HTML

📂 Project Structure
startup-success-prediction
│── app.py
│── train_model.py
│── model.pkl
│── startup.csv
│── templates
│   │── home.html
│   │── adaptivity.html
│   │── result.html
⚙️ How to Run the Project
1️⃣ Install dependencies
pip install pandas numpy scikit-learn flask joblib
2️⃣ Train the model
python train_model.py
3️⃣ Run the Flask app
python app.py
4️⃣ Open in browser
http://127.0.0.1:5000
📊 Dataset

Kaggle – Startup Success Prediction Dataset
https://www.kaggle.com/datasets/manishkc06/startup-success-prediction

📌 Features

✔ Real-time startup success prediction
✔ Probability score output
✔ Simple web interface
✔ Fast response time (< 1 second)

⚠️ Limitations

Limited features in dataset

Does not include market trends or team experience

🔮 Future Scope

Add more business features

Use deep learning models

Deploy on cloud (AWS/Render)

Add investor recommendation system

👩‍💻 Internship

Developed as part of SmartInternz Machine Learning Internship

📬 Author
MV YASWANTH
GitHub: https://github.com/bhargavisai20

