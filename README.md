## 🎮 Google Play Store Exploratory Data Analysis and Machine Learning
As apps become a demanding usage in our daily life, I was wondering the trend of app categories built over time and what kind of app is the most 'needy' for users. Therefore, I took data from the years 2010 to 2018 on Kaggle for data exploration.

Dataset can be downloaded here: https://www.kaggle.com/datasets/lava18/google-play-store-apps

```diff
! To read the full report, please check out the Google Play Store Report
```

### 🎲 **Introduction**
Why Google Play Store?
- Google Play Store is the official app store in Android Market. Most users are required to install applications through Google Play Store.
- Google Play Store is available in various platform, such as Android, Chrome OS.

### 🎲 **Questions**
1. Which category has the highest rating mean?
2. Which category has the highest number of installs?
3. Is there any relationship between high rating and number of installs?
4. Which app has:
  - highest rating
  - highest reviews
  - highest installs
5. What is the trend of app built over time?
6. Which machine learning model fits the most to predict the most successful app?

### 🎲 **Conclusions**
1. The 'Events' category has the highest rating mean. While 'Family' category appears to have the most outliers under its rating mean.
2. The top 3 highest number of install categories are: Game, Communication and Tools.
3. There is a positive relationship between the number of installs and reviews.
4. - The top rating and installs app is 'Ek Bander Ne Kholi Dukan' in the category 'Family' with 10000 installs.
   - The top rating paid app is 'FHR 5-Tier 2.0' in the category 'Medical' with 500 installs.
   - The highest installs and review app is 'Facebook'.
5. From 2014 to 2018, most of the app made are in the category 'Family'. The top 3 number of app categories build are: Family, Game and Tools.
6. In this project, I applied Decision Tree, Logistic Regression, Support Vector Machines and K Nearest Neighbors to train the data. If the app rating is equal or greater than 4.5, it is a successful app.
After training, I conclude that KNN model has the highest f1 score and Jaccard Score (f1 score: 0.612 , Jaccard Score: 0.493). This indicates KNN is the best classification model in predicting a successful app.
