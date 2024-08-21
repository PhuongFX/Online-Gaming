

**Gaming Engagement Prediction**
=====================================

Are you curious about what makes gamers tick? 🤔 Do you want to know how to predict their engagement levels? 📊 Well, you're in the right place! 😊 This project aims to predict the engagement level of gamers based on various factors such as age, gender, location, game genre, playtime hours, and more.

**Model Deployment 🎮**
-----------------

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ml-online-gaming-lvpredict.streamlit.app)

**Dataset 📊**
----------------

Containing 40,034 samples and 13 features. Here's a sneak peek at what's inside:

* `PlayerID`: Unique identifier for each player
* `Age`: Age of the player
* `Gender`: Gender of the player (Male/Female)
* `Location`: Location of the player
* `GameGenre`: Genre of the game played (Strategy, Sports, Action, RPG, Simulation)
* `PlayTimeHours`: Number of hours played
* `InGamePurchases`: Number of in-game purchases made
* `GameDifficulty`: Difficulty level of the game (Easy, Medium, Hard)
* `SessionsPerWeek`: Number of sessions played per week
* `AvgSessionDurationMinutes`: Average duration of each session in minutes
* `PlayerLevel`: Level of the player
* `AchievementsUnlocked`: Number of achievements unlocked
* `EngagementLevel`: Engagement level of the player (Low, Medium, High)


**Architecture 🤖**
------------------

Here's a step-by-step guide to how to approached this project:

1. **Data Preprocessing 🧹**: Removing missing values, encoding categorical variables, and scaling numerical variables.
2. **Exploratory Data Analysis (EDA) 🔍**: Exploring the dataset to understand the distribution of each feature and their relationships.
3. **Modeling 🤖**: Training and evaluating several machine learning models to predict the engagement level of gamers. The models used include:
	* Logistic Regression
	* K-Nearest Neighbors
	* Support Vector Machines
	* Decision Tree
	* Random Forest
	* AdaBoost
	* Gradient Boosting
	* Naive Bayes
	* Neural Network
	* XGB
	* HistGradientBoostingClassifier
	* LGBMClassifier
	* CatBoostClassifier
	* ExtraTreesClassifier
4. **Hyperparameter Tuning 🔧**: Tuning hyperparameters using Bayesian optimization to improve the performance of the models.

**Results 📊**
--------------

The best performing model was the XGB model with an accuracy of 91.64% on the test set. 🎉 Here are the results of the other models:

| Model | Training Accuracy | Test Accuracy |
| --- | --- | --- |
| XGB | 93.39% | 91.64% |
| RandomForest | 92.12% | 91.42% |

**Fine Tuning 📊**
-------------------

<p align='center'>
  <img src="https://github.com/PhuongFX/OnlineGame/blob/main/newplot.png" />
</p>

--------------
Predicting gamer engagement is a complex task, but with the right approach and techniques, we can achieve high accuracy. 📈 This project demonstrates the power of machine learning in understanding gamer behavior and predicting their engagement levels.


**License 📜**
--------------

This project is licensed under the MIT License.


**Get Involved 🤝**
-----------------

I hope you found the project interesting and informative. If you'd like to try out the model or contribute to the project, please let me know! I'd love to hear from you.
* [Follow me on GitHub](https://github.com/PhuongFX)
* [Follow me on Hugging Face](https://huggingface.co/PhuongFX)


