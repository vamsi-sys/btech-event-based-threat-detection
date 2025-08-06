# 🔐 Cyber Threat Detection Using Artificial Neural Networks with Event Profiles

This project implements an AI-based Security Information and Event Management (AI-SIEM) system that detects cyber threats using both deep learning (LSTM, CNN) and classical machine learning (SVM, KNN, Decision Tree, Random Forest, Naïve Bayes) models. The approach is based on event profiling and TF-IDF vectorization of attack signatures.

---

## 🚀 Features

- 📁 **Event Profiling** – Converts raw datasets into structured attack profiles
- 🧠 **Deep Learning Models** – Implements LSTM and CNN for threat detection
- ⚙️ **Traditional ML Models** – SVM, KNN, DT, RF, NB
- 🔍 **PSO Optimization** – Feature selection using Particle Swarm Optimization
- 📈 **Performance Metrics** – Accuracy, Precision, Recall, F-Measure
- 🖥️ **User Interface** – Built using Tkinter for a GUI-based interaction

---

## 🗂️ Project Structure
CyberThreatDetection/
├── datasets/ # Place your CSV dataset(s) here (e.g., kdd_train.csv)
├── CyberThreatDetection.py # Main GUI-based application
├── test.py # CLI-based SVM test script
├── run.bat # Batch file to launch GUI
├── SCREENSHOTS.docx # Contains step-by-step execution screenshots
├── README.md # Project documentation
