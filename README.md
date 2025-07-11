# 💙 Simeon's BMI Calculator
# 🧮 Simeon's BMI Calculator

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bmi-app-5gl5j5le7bs.streamlit.app)

A simple yet informative Body Mass Index (BMI) calculator built using **Streamlit**, designed to help users assess their weight category based on their height and weight inputs.

---

## 📌 Overview

The **Body Mass Index (BMI)** is a quick, non-invasive method used globally to estimate a person's body fat and assess their risk for health issues related to underweight, overweight, or obesity. This application provides:

- An intuitive interface to calculate BMI using various height units (cm, meters, feet).
- Personalized feedback based on the user's BMI classification.
- Health resources and actionable tips depending on the result.

---

## 🚀 Features

- 🌍 **Multi-unit support** for height input (cm, meters, feet)
- 📊 **Instant BMI calculation and category interpretation**
- 🧠 **Health advice** with links to credible sources
- 🧑‍⚕️ Clear warnings for critical BMI ranges
- 🎨 Visually enhanced with images and clean UI using **Streamlit**

---

## 💡 Technologies Used

- [Streamlit](https://streamlit.io/)
- [Python](https://www.python.org/)
- [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/) – for image rendering

---

## 🧪 Limitations

While BMI is a useful general indicator, it doesn't account for factors such as muscle mass, bone density, age, or sex. It should **not** be used as a sole diagnostic tool. Always consult a healthcare professional for comprehensive assessment.

---

## ✅ How to Use

1. Open the [BMI App](https://bmi-app-5gl5j5le7bs.streamlit.app)
2. Enter your name, weight, and height.
3. Choose your height unit (cm, meters, or feet).
4. Click **"Calculate BMI"** to view your results and get health advice.

---

## 📸 Preview

![App Screenshot](https://user-images.githubusercontent.com/your_screenshot_here.jpg)  
*Example of BMI feedback based on input*

---

## 🧑‍💻 Author

**Simeon Ifalore**  
Lead Data Analyst | Data Science Instructor  
🔗 [LinkedIn](https://linkedin.com/in/simeon-ifalore) • 📧 simeon@example.com


Welcome to **Simeon's BMI Calculator** — a simple and interactive web app that helps users check if their weight is in a healthy range for their height using the **Body Mass Index (BMI)** formula.

Built with [Streamlit](https://streamlit.io/), this app offers a friendly interface, health insights, and helpful tips based on your BMI score. It’s ideal for personal use, wellness education, or as a fun demo of beginner Python and Streamlit capabilities.

---

## 📸 App Preview

![BMI Calculator Demo](pexels-pixabay-209887.jpg)

---

## 🧠 What is BMI?

**BMI (Body Mass Index)** is a simple calculation using a person's height and weight. It helps determine if you are underweight, at a healthy weight, overweight, or obese.  
**Note:** This tool is for informational purposes only and should not replace professional medical advice.

---

## 🚀 Features

✅ Easy-to-use interface  
🎯 Choose height in **centimeters**, **meters**, or **feet**  
📊 Instant BMI calculation  
💬 Personalized health messages based on your result  
🔗 Useful external health links  
🖼️ Beautiful embedded image to enhance user experience

---

## 🔧 How to Use

1. Clone or download this repository.
2. Ensure you have Python installed (preferably 3.7 or above).
3. Install required libraries:
    ```bash
    pip install streamlit pillow
    ```
4. Make sure the image file `pexels-pixabay-209887.jpg` is in the same directory as the script.
5. Run the app:
    ```bash
    streamlit run bmi_calculator.py
    ```
6. The app will open in your web browser. Follow the on-screen instructions to enter your name, weight, and height to get your BMI.

---

## 📊 BMI Classification

| BMI Score         | Health Status                      |
|-------------------|-------------------------------------|
| Less than 16      | Extremely underweight 😟             |
| 16 - 18.4          | Underweight ⚠️                      |
| 18.5 - 24.9        | Normal weight 😀                    |
| 25 - 29.9          | Overweight ⚠️                       |
| 30 and above       | Obese 😨                            |

Helpful health resources are provided when necessary.

---

## 🛑 Disclaimer

This tool provides general health information and **should not be used for diagnosis or treatment**. Always consult a licensed healthcare provider for medical advice.

---

## 👨‍💻 Author

**Simeon Ifalore**  
Data & Health-Tech Enthusiast  
Let’s connect on [LinkedIn](https://www.linkedin.com/) or [GitHub](https://github.com/)!

---

## 📁 Project Structure

```bash
├── bmi_calculator.py         # Main Streamlit app
├── pexels-pixabay-209887.jpg  # Embedded image for UI
└── README.md                 # Project description
