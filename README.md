# 📝 Product Review Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.22.0-red)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2.2-orange)

## Business Use Case

Customer reviews hold valuable insights for businesses. Sentiment analysis helps:
- Understand user satisfaction
- Identify product issues
- Improve services based on real feedback

## Features Used

- **Text (Review)** is converted using TF-IDF Vectorization.
- **Model:** Logistic Regression classifier.

## Pipeline Overview

### Training (`model_training.py`)
- Load data
- Preprocess using TF-IDF
- Train Logistic Regression model
- Evaluate and save model

### App (`app.py`)
- Upload new review data
- Run predictions
- Display and download results

## Usage

### 1. Clone the repository
   ```bash
   git clone https://github.com/amitkharche/NLP_sentiment_analysis_project.git
   cd NLP_sentiment_analysis_project

   ```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Train model
```bash
python model_training.py
```

### 4. Run Streamlit app
```bash
streamlit run app.py
```

## 🗂 Project Structure
```
sentiment_analysis_project/
├── data/
├── model/
├── app.py
├── model_training.py
├── requirements.txt
├── README.md
└── .github/
```

## License
This project is licensed under the MIT License.

## Contact

If you have questions or want to collaborate, feel free to connect with me on
- [LinkedIn](https://www.linkedin.com/in/amitkharche)  
- [Medium](https://medium.com/@amitkharche)  
- [GitHub](https://github.com/amitkharche)
