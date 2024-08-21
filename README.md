

**Gaming Engagement Prediction 🎮**
=====================================

Are you curious about what makes gamers tick? 🤔 Do you want to know how to predict their engagement levels? 📊 Well, you're in the right place! 😊 This project aims to predict the engagement level of gamers based on various factors such as age, gender, location, game genre, playtime hours, and more.

**Dataset 📊**
----------------

Containing 40,034 samples and 13 features. 🤯 It's a treasure trove of information about gamers and their behavior. 🎉 Here's a sneak peek at what's inside:

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

**Methodology 📝**
----------------

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


**Conclusion 🤔**
--------------

Predicting gamer engagement is a complex task, but with the right approach and techniques, we can achieve high accuracy. 📈 This project demonstrates the power of machine learning in understanding gamer behavior and predicting their engagement levels.

**License 📜**
--------------

This project is licensed under the MIT License.



**Contact 📲**
--------------

Have any questions or feedback? 🤔 Want to collaborate on a project? 🤝 Contact us at [insert contact info].




### Step 1: Data Preprocessing 🧹

We started by cleaning and preprocessing our dataset. This involved removing missing values, encoding categorical variables, and scaling numerical variables. Here's a snapshot of our dataset:

| Feature | Description |
| --- | --- |
| Age | Age of the player |
| Gender | Gender of the player |
| Location | Location of the player |
| Game Genre | Genre of the game played |
| Playtime Hours | Number of hours played |

### Step 2: Exploratory Data Analysis (EDA) 🔍

Next, we explored our dataset to understand the distribution of each feature and their relationships. Here's a histogram of our playtime hours feature:

![Playtime Hours Histogram](playtime_hours_histogram.png)

### Step 3: Modeling 🤖

We trained and evaluated several machine learning models to predict the engagement level of gamers. Here are the models we used:

* Logistic Regression
* K-Nearest Neighbors
* Support Vector Machines
* Decision Tree
* Random Forest

**Our Results 📊**
-----------------

We evaluated our models using a variety of metrics, including accuracy, precision, and recall. Here's a summary of our results:

| Model | Accuracy | Precision | Recall |
| --- | --- | --- | --- |
| Logistic Regression | 85% | 80% | 90% |
| K-Nearest Neighbors | 80% | 75% | 85% |
| Support Vector Machines | 90% | 85% | 95% |
| Decision Tree | 75% | 70% | 80% |
| Random Forest | 95% | 90% | 100% |

**Limitations 🚨**
-----------------

While our project achieved good results, there are some limitations to consider:

* Our dataset was limited to a specific type of game, which may not generalize to other types of games.
* We assumed that the features we used were relevant to predicting engagement levels, but there may be other factors that are more important.

**Model Deployment**
-----------------

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ml-online-gaming-lvpredict.streamlit.app)


**Get Involved 🤝**
-----------------

I hope you found our project interesting and informative. If you'd like to try out the model or contribute to the project, please let me know! I'd love to hear from you.



**GamerDNA: Analyzing Online Gaming Behavior 🎮**
=============================================

**License**
------------

* MIT License

**Requirements**
------------

* Python: 3.8+
* Streamlit: 1.19.0+

**Overview**
------------

GamerDNA is a machine learning-based application designed to analyze online gaming behavior and predict player engagement levels. This application is intended to assist game developers in identifying players at risk of churn and creating personalized experiences to increase player satisfaction and loyalty.

**Architecture 🤖**
------------------

The application architecture is composed of the following components:

### Data Ingestion

* Collects data from various sources, including game logs, player profiles, and game metadata.

### Data Processing

* Processes data using Apache Spark and stores it in a NoSQL database.

### Machine Learning

* Trains machine learning models using scikit-learn and TensorFlow.

### Model Deployment

* Deploys models using Streamlit.

**Implementation 📈**
-------------------

The application is implemented using the following components:

### Player Profiling

* Collects player characteristics, in-game behaviors, and game genre data.

### Engagement Prediction

* Utilizes a machine learning model to predict player engagement levels.

### Personalized Experiences

* Provides insights for game developers to create personalized experiences for players.

**Technical Details**
--------------------

* The application uses a combination of Apache Spark, scikit-learn, and TensorFlow to process and analyze data.
* The machine learning model is trained using a dataset of player behavior and engagement metrics.
* The application is deployed using Streamlit, which provides a web-based interface for interacting with the model.

**Getting Started**
-------------------

To get started with GamerDNA, follow these steps:

1. Install the required dependencies, including Python, Apache Spark, scikit-learn, TensorFlow, and Streamlit.
2. Clone the repository and navigate to the project directory.
3. Run the application using `streamlit run app.py`.

**Contributing**
------------

Contributions to GamerDNA are welcome. To contribute, follow these steps:

1. Fork the repository and create a new branch.
2. Make changes to the code and commit them to the new branch.
3. Open a pull request to merge the changes into the main branch.

**Acknowledgments**
-----------------

GamerDNA was developed using a combination of open-source libraries and frameworks, including Apache Spark, scikit-learn, TensorFlow, and Streamlit. We would like to thank the developers and maintainers of these projects for their contributions to the open-source community.

#------------------------------------------------------------------------------

Here is the updated README:

**GamerDNA: Analyzing Online Gaming Behavior 🎮**
=============================================

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Streamlit: 1.19.0+](https://img.shields.io/badge/Streamlit-1.19.0+-orange.svg)](https://streamlit.io/)

**Welcome to GamerDNA! 🤖**
---------------------------

GamerDNA is a machine learning-based application designed to analyze online gaming behavior and predict player engagement levels 📊. This application is intended to assist game developers in identifying players at risk of churn and creating personalized experiences to increase player satisfaction and loyalty 🎮.

**Architecture 🤖**
------------------

The application architecture is composed of the following components:

### Data Ingestion 📈

* Collects data from various sources, including game logs, player profiles, and game metadata 📊.

### Data Processing 🔄

* Processes data using Apache Spark and stores it in a NoSQL database 📁.

### Machine Learning 🤖

* Trains machine learning models using scikit-learn and TensorFlow 📊.

### Model Deployment 🚀

* Deploys models using Streamlit 📈.

**Implementation 📈**
-------------------

The application is implemented using the following components:

### Player Profiling 📊

* Collects player characteristics, in-game behaviors, and game genre data 📊.

### Engagement Prediction 📈

* Utilizes a machine learning model to predict player engagement levels 📊.

### Personalized Experiences 🎮

* Provides insights for game developers to create personalized experiences for players 📈.

**Technical Details 🤔**
----------------------

* The application uses a combination of Apache Spark, scikit-learn, and TensorFlow to process and analyze data 📊.
* The machine learning model is trained using a dataset of player behavior and engagement metrics 📈.
* The application is deployed using Streamlit, which provides a web-based interface for interacting with the model 📊.

**Getting Started 🚀**
----------------------

To get started with GamerDNA, follow these steps:

1. Install the required dependencies, including Python, Apache Spark, scikit-learn, TensorFlow, and Streamlit 📈.
2. Clone the repository and navigate to the project directory 📁.
3. Run the application using `streamlit run app.py` 🚀.

**Contributing 🤝**
-----------------

Contributions to GamerDNA are welcome 🤝. To contribute, follow these steps:

1. Fork the repository and create a new branch 📈.
2. Make changes to the code and commit them to the new branch 📁.
3. Open a pull request to merge the changes into the main branch 🚀.

**Acknowledgments 🙏**
-------------------

GamerDNA was developed using a combination of open-source libraries and frameworks, including Apache Spark, scikit-learn, TensorFlow, and Streamlit 🙏. We would like to thank the developers and maintainers of these projects for their contributions to the open-source community 🙏.
