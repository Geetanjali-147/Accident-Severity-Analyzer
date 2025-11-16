# 🚗 Accident Severity Analyzer

An AI-powered web application that analyzes accident images and classifies the severity of vehicle damage using machine learning. Built with Streamlit and Python.

## 📋 Overview

The Accident Severity Analyzer helps insurance companies, emergency responders, and vehicle owners quickly assess the extent of damage from accident images. The system classifies accidents into three severity levels:

- 🟢 **Minor Damage** - Cosmetic damage, scratches, small dents
- 🟡 **Moderate Damage** - Structural damage, airbag deployment
- 🔴 **Severe Crash** - Major structural failure, potential injuries

## ✨ Features

- **Image Upload** - Support for JPG, PNG, and JPEG formats
- **Real-time Analysis** - Instant severity classification with confidence scores
- **User-Friendly Interface** - Clean, intuitive Streamlit UI
- **Actionable Recommendations** - Severity-based next steps and guidance
- **Image Preprocessing** - Automatic image validation and optimization
- **Responsive Design** - Works on desktop and mobile devices

## 🛠️ Installation

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/Geetanjali-147/Accident-Severity-Analyzer.git
cd Accident-Severity-Analyzer
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the application**
```bash
streamlit run app.py
```

4. **Open in browser**

The app will automatically open at `http://localhost:8501`

## 📦 Project Structure

```
Accident-Severity-Analyzer/
│
├── app.py              # Main Streamlit application
├── models.py           # ML model and prediction logic
├── utils.py            # Image preprocessing utilities
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── __pycache__/        # Python cache (ignored)
```

## 📝 Requirements

```
streamlit>=1.28.0
Pillow>=10.0.0
numpy>=1.24.0
```

## 🎯 Usage

1. **Launch the app** using `streamlit run app.py`
2. **Upload an image** - Click "Choose an accident image" button
3. **Wait for analysis** - The AI model processes your image
4. **View results** - See severity classification and confidence score
5. **Follow recommendations** - Get guidance based on damage level
