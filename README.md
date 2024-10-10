# **🚀 Spam Email Detection System**

The Spam Email Detection System is a machine learning project that classifies email content as either "Spam" or "Not Spam" using various natural language processing techniques and machine learning algorithms. The system includes a Flask-based web interface for users to input email text and receive predictions in real time.

## **📑 Table of Contents:**
1. [Overview](#overview)
2. [Technologies](#technologies)
3. [Features](#features)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Screenshots](#screenshots)
7. [Contributing](#contributing)

---

## **🌟 Overview:**

This project leverages machine learning to detect spam emails. Using techniques such as **Term Frequency-Inverse Document Frequency (TF-IDF)** for text feature extraction and models like **Support Vector Machines (SVM)**, **Naive Bayes**, and **K-Nearest Neighbors (KNN)**, the system achieves high accuracy in spam classification. The project is hosted locally with Flask and allows users to test emails by submitting the text via a web interface.

---

## **💻 Technologies:**

- **Python** (NLTK, Scikit-learn, Flask)
- **Flask** (for the web interface)
- **AWS EC2** (for deployment)
- **Machine Learning Models**:
  - Support Vector Machines (**SVM**)
  - Naive Bayes (**Gaussian, Multinomial, Bernoulli**)
  - K-Nearest Neighbors (**KNN**)
- **Frontend**: HTML, CSS

---

## **🚀 Features:**

- **User-friendly interface** to input email text.
- **Real-time spam detection** using pre-trained models.
- Models trained on a large email dataset for **high accuracy**.
- Achieved over **95% accuracy** with the SVM model.

---

## **⚙️ Installation:**

1. Clone the repository:
    ```bash
    git clone https://github.com/ajit1630/Spam-Email-Detection-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Spam-Email-Detection-System
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Flask app:
    ```bash
    python app.py
    ```

---

## **🖼️ Screenshots:**

### **✅ Not Spam**
![Not Spam Email](https://github.com/user-attachments/assets/70d183a2-8385-404d-9122-be66772d9a7c)

*Description: A clean and professional email layout with a well-structured message, indicating that it is not spam.*

### **🚫 Spam**
![Spam Email](https://github.com/user-attachments/assets/938ff047-684b-4dbc-8cc2-73ecf3370a41)

*Description: An email with a chaotic and cluttered layout, highlighting the typical red flags of spam emails.*

---

## **🤝 Contributing:**

Contributions are welcome! Please fork this repository and submit a pull request.  
Join us in discussions, and let's build something awesome together!

---

Thank you for checking out the project! 🎉
