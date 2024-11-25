# Phishing Domain Detection

This project detects phishing websites based on their domain characteristics using machine learning models and a web-based interface.

---

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Dataset](#dataset)  
6. [Model Development](#model-development)  
7. [Web Interface](#web-interface)  
8. [Contributing](#contributing)  
9. [License](#license)

---

## Overview

The **Phishing Domain Detection** project is an end-to-end solution for identifying malicious phishing websites. It includes a machine learning model to classify domains and a user-friendly interface for real-time predictions.

---

## Features

- **Machine Learning Pipeline**: Data preprocessing, model training, and evaluation.  
- **Web-based Interface**: A simple interface built with HTML, CSS, and Flask for domain detection.  
- **Real-time Predictions**: Predicts whether a domain is legitimate or a phishing attempt.  

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/parasmunoli/Phishing-Domain-Detection.git
   cd Phishing-Domain-Detection
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
3. Run the Flask server:
   ```bash
   python app.py
   ```

## Usage

1. **Machine Learning:** Use the Jupyter notebooks provided in the `Machine Learning` folder to train or evaluate the model.  
2. **Web Application:**
    - Access the web interface by running the Flask server.  
    - Input a domain name to predict its legitimacy.

## Dataset
The project uses a dataset containing features like:  

- Domain length.  
- Presence of special characters.  
- Suspicious keywords.  

## Model Development
- Algorithm Used: Random Forest (or customizable options).
- Steps:
    - Preprocess data using Python scripts.
    - Train and save the model for deployment.