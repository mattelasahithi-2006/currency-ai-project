# AI-Powered Global Currency Analyzer: Recognition, Conversion, and Educational Portal

An intelligent web application that recognizes currency notes using Deep Learning, converts currencies in real time, and provides educational information about different currencies around the world.

---

## Project Overview

The **AI-Powered Global Currency Analyzer** helps users identify currency notes from uploaded images, perform currency conversion, and learn about various currencies and their security features.

This project combines **Artificial Intelligence**, **Computer Vision**, **Flask APIs**, and **MongoDB** to provide an interactive and informative platform for travelers, students, and users dealing with multiple currencies.

---

##  Features

###  Currency Recognition

* Upload an image of a currency note.
* Detects the currency type and denomination using a trained deep learning model.
* Supports multiple countries' currencies.

### Currency Conversion

* Converts recognized currency values into other currencies.
* Uses real-time exchange rates through an API.

###  Educational Portal

* Displays currency information such as:

  * Country name
  * Currency code
  * Currency symbol
  * Security features
  * Sample images

### 🌐 User-Friendly Interface

* Responsive frontend built with HTML, CSS, and JavaScript.
* Simple image upload and result display.

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask

### Artificial Intelligence

* TensorFlow
* Keras
* MobileNetV2 (Transfer Learning)

### Database

* MongoDB

### APIs

* Exchange Rate API

---

##  System Architecture

```
User
  ↓
Frontend (HTML, CSS, JavaScript)
  ↓
Flask APIs
 ├── Currency Recognition Service
 ├── Currency Conversion Service
 └── Educational Information Service
  ↓
TensorFlow Model + MongoDB + Exchange Rate API
```

---

## 📂 Project Structure

```
Currency-Analyzer/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── recognition_service/
│   ├── app.py
│   ├── predict.py
│   ├── models/
│   │     └── best_currency_model.keras
│   ├── dataset/
│
├── conversion_service/
│   ├── app.py
│
├── education_service/
│   ├── app.py
│
├── requirements.txt
└── README.md
```

---

##  Deep Learning Model

The currency recognition module uses **MobileNetV2 Transfer Learning**.

### Image Preprocessing

* Image Size: 224 × 224
* Data Augmentation:

  * Rotation
  * Zoom
  * Width and Height Shift
  * Brightness Adjustment

### Training Techniques

* Early Stopping
* Reduce Learning Rate on Plateau
* Model Checkpointing

---

##  Supported Currency Classes

### Indian Rupee (INR)

* ₹10
* ₹20
* ₹50
* ₹100
* ₹200
* ₹500

### US Dollar (USD)

* $1
* $2
* $5
* $10
* $50
* $100

### Thai Baht (THB)

* ฿20
* ฿50
* ฿100
* ฿500
* ฿1000

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/currency-analyzer.git
cd currency-analyzer
```

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/Mac**

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Services

### Currency Recognition Service

```bash
python app.py
```

Runs on:

```
http://localhost:5002
```

### Currency Conversion Service

```bash
python app.py
```

Runs on:

```
http://localhost:5000
```

### Educational Service

```bash
python app.py
```

Runs on:

```
http://localhost:5001
```

---

## Applications

* Currency identification for travelers.
* Educational platform for learning about world currencies.
* Assistance for visually impaired users.
* Financial awareness and international exchange learning.

---

## Future Enhancements

* Add more countries and currencies.
* Support coin recognition.
* Mobile application integration.
* Voice assistance for accessibility.
* Offline currency recognition.

---



Developed as an academic mini project using:

* Python
* Flask
* TensorFlow
* Keras
* MongoDB
* HTML, CSS, JavaScript

---
.
