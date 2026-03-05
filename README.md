🏡 End-to-End House Price Prediction Using Supervised Regression Models and Web-Based Deployment

A complete Machine Learning + Flask web application that predicts house prices using key property parameters such as area, quality, bedrooms, bathrooms, and garage capacity.

This project demonstrates a full end-to-end ML deployment pipeline — from data preprocessing → model training → saving the model → Flask integration → UI for prediction.

🚀 Features

✔ Interactive web UI for entering house details

✔ ML model trained using real housing data

✔ End-to-end pipeline: preprocessing → training → deployment

✔ Fast predictions powered by Flask backend

✔ Clean input form + result page

✔ Beginner-friendly and portfolio-ready

🧠 Machine Learning Workflow
📌 Data Preprocessing

Handled missing values

Removed outliers

Encoded categorical features

Applied feature scaling

Train-test split

📌 Model Training

Models used: Linear Regression / Random Forest

Evaluated using R² Score, Mean Squared Error

📌 Model Saving

Used pickle to serialize the trained model

Flask loads the model for instant predictions
```
🏗️ Project Structure
House-Price-Prediction/
│
├── app.py               # Flask backend
├── model.pkl            # Trained ML model
├── scaler.pkl           # Scaler (if used)
│
├── templates/
│   ├── index.html       # Input page
│   └── result.html      # Output page
│
├── static/
│   └── style.css        # Styling
│
├── screenshots/
│   ├── homepage.jpg
│   ├── form.jpg
│   └── result.jpg
│
└── README.md
```
🖥️ How to Run Locally
1️⃣ Install Required Libraries
pip install flask pandas numpy scikit-learn

2️⃣ Run the App
python app.py

3️⃣ Open in Browser
http://127.0.0.1:5000

📥 Input Fields

Users enter the following property features:

Lot Area (sq ft)

Overall Quality (1–10)

Year Built

Total Basement Area

Living Area (sq ft)

Full Bathrooms

Bedrooms Above Ground

Garage Capacity

📤 Output

The app predicts the House Price in USD using the trained ML model.

🏠 Home Page
![WhatsApp Image 2025-10-26 at 15 25 00_3d36baf9](https://github.com/user-attachments/assets/922d36db-1155-4105-ac49-ce029ee3e461)

📝 Input Form
![WhatsApp Image 2025-10-26 at 15 25 00_e1d8c573](https://github.com/user-attachments/assets/2e64411f-0430-4a3d-8b51-03db12738d91)

📊 Predicted Result
![WhatsApp Image 2025-10-26 at 15 22 39_0b53b57b](https://github.com/user-attachments/assets/a97af8bb-1396-48e2-bdb7-ed66ce4a369f)

🎯 Purpose of the Project

This project is ideal for:

Students learning ML deployment

Resume / GitHub portfolio projects

Flask beginners

College mini-projects

Understanding end-to-end ML pipelines

🛠️ Technologies Used

Python

Flask

Scikit-Learn

Pandas / NumPy

HTML / CSS

🤝 Contributing

Pull requests, improvements, and suggestions are always welcome!

📜 License

This project is licensed under the MIT License.

⭐ Support

If you found this project helpful, please give the repository a ⭐ to support the work!
