# NEET Rank Predictor

# Project Overview

This project is designed to analyze NEET Testline quiz performance and predict student ranks based on their current and historical quiz data. The model also extends its capabilities to predict the most likely college a student can be admitted to, based on their predicted NEET rank.

# Features

Data Analysis: Identifies performance trends by topics, difficulty levels, and response accuracy.

Insight Generation: Highlights weak areas, improvement trends, and performance gaps.

Rank Prediction: Uses a probabilistic model to predict NEET ranks based on quiz performance.

College Prediction (Bonus): Suggests potential colleges based on the predicted rank.

# Tech Stack

Backend: Python (Flask for API)

Data Analysis: Pandas, NumPy

Machine Learning: Scikit-learn

Visualization: Matplotlib, Seaborn

Frontend (Optional): React.js for UI

# Setup Instructions

Clone the repository:

```
git clone https://github.com/vinod8833/neet_rank.git

```
```
cd neet_rank
```

# API Endpoints

POST /quiz_submission: Analyzes the latest quiz data.

GET /historical_data/{user_id}: Fetches historical quiz data for a specific user.

POST /predict_rank: Predicts NEET rank based on combined data.

POST /predict_college: Suggests potential colleges.

# Data Overview

Current Quiz Data:

Quiz title, scores, topics, responses, accuracy, submission time.

Historical Quiz Data:

Scores from the last 5 quizzes.

Response maps (Question ID vs. Selected Option).

# Sample Inputs & Outputs

Input: User's latest quiz submission + historical data.

Output: Predicted NEET rank and recommended colleges.

# 📸 Screenshots

![Quiz Performance Dashboard](https://github.com/vinod8833/neet_rank/blob/main/Student_Rank/images/image.png?raw=true)

![Accuracy Graph](https://github.com/vinod8833/neet_rank/blob/main/Student_Rank/images/image-1.png?raw=true)

![Rank Prediction Chart](https://github.com/vinod8833/neet_rank/blob/main/Student_Rank/images/image-2.png?raw=true)

![Improvement Trends](https://github.com/vinod8833/neet_rank/blob/main/Student_Rank/images/image-3.png?raw=true)


# Demonstration Video

link: https://drive.google.com/file/d/1FUoF24LF2McVVNK-gK42kVV3pi-6Dvfr/view?usp=sharing

# Contributors

Vinod Kumar