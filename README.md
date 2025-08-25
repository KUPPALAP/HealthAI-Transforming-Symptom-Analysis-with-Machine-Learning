HealthAI – Transforming Symptom Analysis with Machine Learning
 Project Overview

HealthAI is an intelligent system that predicts possible diseases based on user-entered symptoms. It is designed to improve healthcare accessibility, especially in underserved regions, by providing reliable self-assessment support through machine learning models.

Key Contributions:

Built models to map symptoms → diseases.

Evaluated multiple ML algorithms with strong performance.

Designed for individuals with limited healthcare access, including rural areas and non-specialist caregivers.

Proposed real-world deployment as a chatbot, mobile app, or telemedicine integration.

 Project Structure

Ai_in_Health_Care_Project_(1)-2-1.ipynb → Jupyter Notebook with preprocessing, training, and evaluation code.

Ai Symptom2Disease-1-1.csv → Dataset (4,900+ patient records, symptoms + disease labels).

AI HealthAI – Transforming Symptom Analysis with Machine Learning.pptx → Project slides with problem, methods, and results.

README.md → Documentation file.

 Dataset & Preprocessing

Dataset: 4,900+ records with symptoms and associated diseases.

Preprocessing steps:

Cleaned inconsistent entries.

Tokenized symptom text.

Converted to machine-readable format using TF-IDF.

Goal: Ensure structured, reliable data to support accurate predictions.

 Machine Learning Models Used

We tested multiple models to balance speed and accuracy:

Logistic Regression – Baseline, interpretable.

Naïve Bayes – Lightweight, efficient on text.

SVM – High accuracy in high-dimensional space.

Random Forest – Best accuracy at 97.5%.

Gradient Boosting – Strong performance at 84.1%.

 Results & Evaluation

Random Forest achieved 97.5% accuracy.

Evaluation metrics: Confusion matrices, precision, recall, F1-score.

Cross-validation confirmed robustness and generalizability.

Predictions aligned with clinical reasoning (e.g., fever + cough → flu).

 Practical Impact

AI-powered digital health assistant for early triage.

Can be integrated into:

Chatbots for 24/7 self-assessment.

Rural telemedicine kits.

Offline/mobile versions for low-connectivity areas.

 Limitations & Future Enhancements

Current dataset does not capture symptom severity or progression over time.

Limited rare/complex disease coverage.

TF-IDF misses contextual meaning of symptoms.

Future Directions:

Use LSTM / Transformer models (BERT, BioBERT) for contextual understanding.

Train with real-world EMR datasets.

Add multilingual/voice input for accessibility.

Apply explainability tools (SHAP, LIME) for clinical trust.

Build a Streamlit/Gradio UI for deployment.

 References

Siddiqui et al. (2020). ML for Neurological Diagnosis. Brain Informatics.

Johnson & Lee (2021). Deep Learning for Medical NLP. AI in Medicine Journal.

Devlin et al. (2019). BERT: Pre-training Transformers for Language Understanding.

CDC (2022). Symptoms and Associated Diseases.

MedlinePlus (2023). Symptom Checker & Disease Identification.

 Team

Karunakar Uppalapati

Varshitha Reddy Davarapalli



