This project explores the impact of social media usage on students' tiredness upon waking up. Using a small dataset of 21 students, we apply various statistical and machine learning methods to identify patterns and make predictions.

Dataset
Rows: 22 (including header)

Columns: 12

Data Points: Self-reported usage of social media platforms and sleep-related indicators

Data Dictionary
Column Name	Description
Dataset ID	Unique identifier for each student
Instagram Usage	Time spent on Instagram
LinkedIn Usage	Time spent on LinkedIn
Snapchat Usage	Time spent on Snapchat
Twitter Usage	Time spent on Twitter
Whatsapp Usage	Time spent on WhatsApp
YouTube Usage	Time spent on YouTube
OTT Usage	Time spent on streaming platforms
Reddit Usage	Time spent on Reddit
Trouble Falling Asleep	0 = No, 1 = Yes
Mood Productivity	0 = Bad, 1 = Good
Tiredness Upon Waking Up	0 = Low, 1 = High

Objectives
Can we find a relationship between social media usage and morning tiredness?
Can we predict tiredness upon waking using social media usage patterns?

Methods Used
Correlation Matrix to explore relationships between variables
PCA (Principal Component Analysis): Tested for dimensionality reduction, but not ideal (variance < 70%)
EFA (Exploratory Factor Analysis): Extracted 4 meaningful components
RC1: Content Engagement (Twitter, Reddit)
RC2: Social Media Usage (Instagram, Snapchat, LinkedIn)
RC3: Communication & Entertainment (WhatsApp, OTT)
RC4: Information Consumption (YouTube)
Clustering: Used to group sleep patterns
Logistic Regression: Used to predict tiredness levels

Results
Logistic regression performed well in classifying tiredness, with 71% accuracy.
ROC curve showed reliable performance.
Insights suggest social media patterns can predict sleep-related tiredness in students.

Conclusion
Social media usage—especially platform-specific habits—can be used as a predictor of morning tiredness. The logistic regression model was most effective in identifying students at risk for sleep issues based on app usage.


Tools & Libraries
Python
Pandas, NumPy
Matplotlib, Seaborn
scikit-learn
FactorAnalyzer

Future Work
Expand dataset for more generalizable results
Include variables like screen time after 10 PM or caffeine consumption
Compare supervised vs unsupervised models for better predictions
