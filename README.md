# Health Prediction System

## 🚀 Demo

### Full Demo Video
<video src="[assets/demo.mp4](https://github.com/gonthina-dinesh/Disease-prediction-using-artificial-intelligence/blob/main/assets/demo.mp4)" width="100%" controls="controls"></video>


## Overview
The **Health Prediction System** is a web application that helps users assess their risk for various health conditions, including **heart disease, diabetes, and stroke (brain disease)**. Using **Machine Learning models**, the system takes user input, processes it, and provides a health risk assessment along with personalized recommendations.

## Features
- **User Authentication**: Register and log in to access health predictions.
- **Health Predictions**:
  - Heart Disease Risk Prediction
  - Diabetes Risk Prediction
  - Stroke (Brain Disease) Risk Prediction
- **Personalized Health Advice**: Users receive tailored health improvement suggestions based on their results.
- **Secure & Private**: User data is protected and used only for predictions.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **Machine Learning Models**: scikit-learn, pandas, NumPy
- **Database**: SQLite (or any preferred database for user management)

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed.

### Clone the Repository
```bash
 git clone https://github.com/your-username/health-prediction-system.git
 cd health-prediction-system
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python app.py
```

Open your browser and go to **http://127.0.0.1:5000/** to use the application.

## Usage Guide
1. **Sign up / Log in** to access the system.
2. Select a prediction model (**Heart, Diabetes, or Brain Disease**).
3. Enter your health details.
4. Click "Predict" to get your health risk assessment.
5. View recommendations to improve your health.

## Machine Learning Models
The system uses trained **ML models** for health risk prediction:
- **Heart Disease**: Logistic Regression / XGBoost
- **Diabetes**: Decision Tree / Random Forest
- **Brain Disease (Stroke Prediction)**: Support Vector Machine (SVM)

Models are saved using `pickle` and loaded for predictions.

## Future Enhancements
- **Integration with Electronic Health Records (EHR)**
- **Advanced AI Chatbot for medical consultation**
- **More ML models with improved accuracy**
- **Mobile app version**

## Contributing
Feel free to **fork** this repository and make improvements. Pull requests are welcome!

## License
This project is licensed under the **MIT License**.

## Contact
For any issues or suggestions, reach out to:
- **Gonthina Dinesh**: (mailto:gonthina.dinesh2005@gmail.com)

---
Enjoy using the Health Prediction System! 🚀
