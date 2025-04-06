**This project explores the impact of social media usage on students' tiredness upon waking up. Using a small dataset of 21 students, we apply various statistical and machine learning methods to identify patterns and make predictions.**<br>
<br>
## **Dataset**<br>
* Rows: 22 (including header)<br>
* Columns: 12<br>
* Data Points: Self-reported usage of social media platforms and sleep-related indicators<br>
<br>

**Data Dictionary**
* Dataset ID	- Unique identifier for each student<br>
* Instagram Usage	- Time spent on Instagram<br>
* LinkedIn Usage - 	Time spent on LinkedIn<br>
* Snapchat Usage - Time spent on Snapchat<br>
* Twitter Usage	- Time spent on Twitter<br>
* Whatsapp Usage - Time spent on WhatsApp<br>
* YouTube Usage	-Time spent on YouTube<br>
* OTT Usage - Time spent on streaming platforms<br>
* Reddit Usage - Time spent on Reddit<br>
* Trouble Falling Asleep - 0 = No, 1 = Yes<br>
* Mood Productivity - 0 = Bad, 1 = Good<br>
* Tiredness Upon Waking Up - 0 = Low, 1 = High<br>
<br>
**Objectives**
* Can we find a relationship between social media usage and morning tiredness?<br>
* Can we predict tiredness upon waking using social media usage patterns?<br>
<br>
**Methods Used**
* Correlation Matrix to explore relationships between variables<br>
* PCA (Principal Component Analysis): Tested for dimensionality reduction, but not ideal (variance < 70%)<br>
* EFA (Exploratory Factor Analysis): Extracted 4 meaningful components<br>
* RC1: Content Engagement (Twitter, Reddit)<br>
* RC2: Social Media Usage (Instagram, Snapchat, LinkedIn)<br>
* RC3: Communication & Entertainment (WhatsApp, OTT)<br>
* RC4: Information Consumption (YouTube)<br>
* Clustering: Used to group sleep patterns<br>
* Logistic Regression: Used to predict tiredness levels<br>
<br>
**Results**
* Logistic regression performed well in classifying tiredness, with 71% accuracy.<br>
* ROC curve showed reliable performance.<br>
* Insights suggest social media patterns can predict sleep-related tiredness in students.<br>
<br>
**Conclusion**
Social media usage—especially platform-specific habits—can be used as a predictor of morning tiredness. The logistic regression model was most effective in identifying students at risk for sleep issues based on app usage.<br>
<br>

**Tools & Libraries**
* Python<br>
* Pandas, NumPy<br>
* Matplotlib, Seaborn<br>
* scikit-learn<br>
* FactorAnalyzer<br>
<br>
**Future Work**
* Expand dataset for more generalizable results<br>
* Include variables like screen time after 10 PM or caffeine consumption<br>
* Compare supervised vs unsupervised models for better predictions<br>
