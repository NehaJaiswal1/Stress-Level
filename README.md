📊 Stress Level Prediction Project
📌 Overview

This project analyzes and predicts stress levels among students using various psychological, academic, and lifestyle factors.
The dataset includes features like anxiety level, self-esteem, mental health history, depression, sleep quality, study load, social support, bullying, etc.

The goal is to:

Explore patterns in stress and related factors

Visualize relationships (e.g., anxiety level vs. stress level)

Build a machine learning model to classify stress levels

Identify the top factors influencing stress

🗂 Dataset

The dataset contains the following columns:

anxiety_level

self_esteem

mental_health_history

depression

headache

blood_pressure

sleep_quality

breathing_problem

noise_level

living_conditions

safety

basic_needs

academic_performance

study_load

teacher_student_relationship

future_career_concerns

social_support

peer_pressure

extracurricular_activities

bullying

stress_level (Target variable)

⚙️ Approach

Data Preprocessing

Encoded categorical features

Separated features (X) and target (y)

Exploratory Data Analysis (EDA)

Visualized anxiety, sleep quality, academic pressure vs. stress

Boxplots and distributions

Model Training

Used Random Forest Classifier for stress level prediction

Evaluated using classification report (precision, recall, F1-score)

Feature Importance

Extracted top 5 features influencing stress

Visualized with a bar chart

📈 Results

The model can classify stress levels with good accuracy

Top factors influencing stress (example):

Anxiety Level

Sleep Quality

Academic Performance

Study Load

Depression

(Note: Exact top features may vary based on dataset version and training split.)

🛠 Technologies Used

Python

Pandas, NumPy → Data handling

📌 Future Work

Try advanced models (XGBoost, Neural Networks)

Build a dashboard with Power BI / Streamlit

Deploy model as a web app for interactive stress prediction
Matplotlib, Seaborn → Visualization

Scikit-learn → Machine Learning
