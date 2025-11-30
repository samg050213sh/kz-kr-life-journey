🇰🇿🇰🇷 KZ–KR Life Journey Analysis

A personal data-science project about adapting from Kazakhstan to South Korea (2019–2025)
Using Python, statistics, visualizations, and machine learning.

📌 Overview

This project analyzes my emotional, social, and academic journey after moving from Kazakhstan to South Korea at age 17.
Using self-recorded metrics (stress, happiness, Korean level, belonging, friends, sleep, etc.), I explore:
 • 📊 Life trends over 7 years (2019–2025)
 • 💙 Emotional adaptation between two countries
 • 👥 Social changes after immigration
 • 🧠 Stress vs Happiness dynamics
 • 🤖 A machine learning model predicting my happiness
 • 🇰🇿 Nostalgia for Kazakhstan
 • 🇰🇷 Growing sense of belonging in Korea

This project is both a technical assignment and a personal reflection of living abroad.

📁 Project Structure

kz-kr-life-journey/
│
├── data/
│   ├── life_data.csv
│   ├── photos_kz/
│   └── photos_kr/
│
├── results/
│   ├── graphs/
│   │   ├── korean_level.png
│   │   ├── stress_vs_happiness.png
│   │   ├── friends_count.png
│   │   ├── sleep_quality.png
│   │   ├── emotional_transition.png
│   │   └── real_vs_predicted_happiness.png
│   └── correlation_matrix.csv
│
├── src/
│   └── (python scripts)
│
└── 01_data_exploration.ipynb

📊 1. Key Visualizations

🇰🇷 Korean Level Growth

Shows language improvement from 0 → TOPIK 5.

😰 Stress vs 😊 Happiness

Clear cycles of burnout and recovery, especially during adaptation years.

👫 Friends Count Over Years

Social circle shrinking after immigration and slowly rebuilding.

😴 Sleep Quality

Sleep patterns becoming unstable in university years.

💙 Emotional Transition (KZ → KR)

Strong nostalgia during early years, rising belonging in later years.

🤖 2. Machine Learning Model

A Linear Regression model predicts my happiness using:
 • stress
 • friends_count
 • sleep_quality
 • korean_level
 • nostalgia_kz
 • belonging_kr

📈 Coefficients

Feature Effect
Stress –6.02
Friends count –4.06
Sleep quality –0.21
Korean level –8.42
Nostalgia for Kazakhstan +0.76
Belonging to Korea +2.80

🔍 Interpretation
 • Stress significantly lowers happiness
 • Korean level has a negative coefficient because the hardest years (2022–2023) were also years of intense study
 • More belonging in Korea strongly increases happiness
 • Nostalgia for Kazakhstan has a small positive effect
 • Number of friends does not correlate positively with happiness

📉 Model Accuracy

The model predicts happiness perfectly on this dataset:

🧠 3. Insights
 • My emotional wellbeing depends more on identity and belonging than on social or academic metrics.
 • Immigration years (2022–2023) were stressful but transformative.
 • Happiness grows when Korea starts to feel like “home”.
 • Burnout periods match intense study phases (language courses, university).
 • Sleep has surprisingly weak correlation to happiness compared to stress and belonging.

🔧 4. How to Run This Project

pip install pandas numpy matplotlib scikit-learn

Run the notebook:

01_data_exploration.ipynb

Or open directly in Google Colab.

📝 5. Future Improvements
 • Add more years of data
 • Add photos visualization timeline
 • Use more advanced ML models (Random Forest, Gradient Boosting)
 • Build a small web dashboard with Streamlit
 • Add sentiment analysis of journal entries

📄 License

MIT License.
