Wearable-M.AI.E: Wearable Seizure Detection System
!Project Banner

Wearable-M.AI.E is an open-source project that aims to detect and predict epileptic seizures using wearable devices and machine learning. By analyzing physiological signals, our system provides early warnings for seizure events, potentially improving the quality of life for individuals with epilepsy.

Features
Real-time monitoring of physiological data (heart rate, skin conductance, temperature).
Machine learning model for seizure detection.
Secure user authentication using Microsoft Azure Active Directory.
Seamless integration with wearable devices.
Screenshots
!Screenshot 1 Real-time data visualization

!Screenshot 2 Seizure prediction alert

Architecture
!System Architecture

Wearable Device: Collects physiological data from sensors.
Data Preprocessing: Cleans and preprocesses raw signals.
Machine Learning Model: Trained to detect seizure patterns.
Azure Backend: Handles data flow, authentication, and API endpoints.
User Interface: Web or mobile app for users.
Getting Started
Clone the repository:
git clone https://github.com/FLmulti-verse/Wearable-M.AI.E.git

Install dependencies:
cd Wearable-M.AI.E
pip install -r requirements.txt

Set up Azure AD:
Create an Azure AD tenant.
Configure client ID and secret in config.yaml.
Train the model:
Use labeled seizure data to train the machine learning model.
Save model weights as model_weights.pth.
Run the backend:
python backend.py

Access the UI:
Open index.html in your browser.
Contributing
We welcome contributions! Whether you’re a machine learning expert, frontend developer, or domain specialist, there’s a place for you in our community. Check out our contribution guidelines to get started.

License
This project is licensed under the MIT License. See LICENSE for details.
