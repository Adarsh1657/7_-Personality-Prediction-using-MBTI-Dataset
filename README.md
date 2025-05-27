# 🧠 Personality Prediction using MBTI Dataset

This project focuses on predicting personality types based on textual data using the **MBTI (Myers-Briggs Type Indicator)** dataset. It leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to classify users into one of 16 MBTI personality types.
## 👥 Group Members
- Anwesha Singhal
- Adarsh Kumar  
- Animesh Pratap Singh  
- Akul Sharma
- Ashish Gupta

## 📁 Dataset
The dataset used is the [MBTI 1.0 dataset](https://www.kaggle.com/datasnaek/mbti-type) which contains:
- **Posts**: Text data (50 posts per user concatenated)
- **Type**: One of the 16 MBTI personality types (e.g., INFP, ENTP)

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- NLTK (stopwords, lemmatizer)
- Scikit-learn (TF-IDF, Logistic Regression, LabelEncoder)
- Regular Expressions (Regex)

## 🧹 Data Preprocessing
1. Lowercasing text
2. Removing URLs and special characters
3. Removing stopwords
4. Lemmatizing words

## 📊 Feature Extraction
- **TF-IDF Vectorization** with 5000 features to convert text into numerical form.

## 🔍 Model
- **Logistic Regression** classifier with `max_iter=1000`
- Performance evaluated using `classification_report`

## 🧪 Evaluation
- Classification Report includes:
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **Accuracy**
- Model shows better performance on well-represented types like INFP and INTJ.

## 🔁 Future Improvements
- Implement class balancing techniques like SMOTE
- Experiment with deep learning models (e.g., BERT)
- Use dimensionality reduction (e.g., PCA, TruncatedSVD)
- Add a web interface using Streamlit or Flask

## 📎 How to Run
1. Clone this repository
2. Install required packages using `pip install -r requirements.txt`
3. Run the notebook or script:
```bash
python mbti_personality_prediction.py
