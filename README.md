# 🎥 Video Toxicity Detection System

## 📌 Project Overview

The **Video Toxicity Detection System** is an NLP-based application that analyzes speech from video and audio files and identifies potentially toxic content from the generated transcript.

The system extracts audio from supported video files, converts speech into text using speech recognition, processes the transcript using NLP techniques, and performs toxicity analysis using a trained machine learning model.

The project also includes a **Gradio-based interface** that allows users to upload a video and receive both the generated transcript and toxicity analysis.

## 🚀 Key Features

* 🎥 Video/audio file processing
* 🔊 Audio extraction from video
* 🗣️ Speech-to-text conversion
* 🧹 NLP text preprocessing
* 📊 TF-IDF based text vectorization
* 🤖 Machine learning-based toxicity prediction
* 📈 Toxicity category probability analysis
* 🌐 Interactive Gradio interface
* 📝 Video transcript generation

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* TF-IDF
* LightGBM
* SpeechRecognition
* PyDub
* MoviePy
* Matplotlib
* Seaborn
* Gradio

## 🔄 Project Workflow

```text
Video / Audio Input
        ↓
Audio Extraction
        ↓
Speech-to-Text
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Trained ML Model
        ↓
Toxicity Analysis
        ↓
Gradio Interface
        ↓
Transcript + Analysis
```

## 📂 Project Structure

```text
Video-Toxicity-Detection-System/
│
├── notebooks/
│   └── Toxic_Video_App_Formats.ipynb
│
├── models/
│   ├── Toxic_lightgbm_model.pkl
│   └── Toxic_tfidf_vectorizer.pkl
│
├── sample/
│   └── README.md
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 🧠 Toxicity Categories

The notebook analyzes the following toxicity-related categories:

* Toxic
* Severe Toxic
* Obscene
* Threat
* Insult
* Identity Hate

The prediction function evaluates the probabilities associated with these categories and generates a toxicity analysis based on the model output.

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Video-Toxicity-Detection-System.git
```

Move into the project directory:

```bash
cd Video-Toxicity-Detection-System
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Open the notebook:

```text
notebooks/Toxic_Video_App_Formats.ipynb
```

Run the cells sequentially.

The project also provides a Gradio interface for video analysis.

## 🌐 Gradio Application

The Gradio interface accepts a video file and returns:

1. Generated video transcript
2. Toxicity analysis

The interface is created using the Gradio `Interface` API.

## ⚠️ Notes

The speech-to-text component uses Google's speech recognition service through the `SpeechRecognition` package, so speech recognition may require an internet connection.

The notebook was originally developed in Google Colab. Some file paths were therefore adapted for use in the GitHub project structure.

## 🎯 Learning Outcomes

This project provided practical experience with:

* Natural Language Processing
* Text preprocessing
* TF-IDF vectorization
* Machine learning classification
* Speech-to-text processing
* Audio/video processing
* Python automation
* Gradio application development

## 👨‍💻 Author

**Raj Yadav**

B.Tech Computer Science
AI/ML & Generative AI Enthusiast
