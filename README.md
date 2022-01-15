# Spyros Vizirgianakis

Physiotherapist and Sports/Clinical Data Scientist

# *About*
Hi my name is Spyros, I am a physiotherapist and I love data science and Python. I believe data science can be a powerful tool in sports science and clinical practice, because it provides objectivity in decision making and complements domain expertise. Data science can be useful in injury prevention, performance prediction in sports and personalized selection of treatment/rehabilitation.

# *My Projects*
## **1. Elder Fallers Prediction**
![alt text](Fallers_SVMDecisionBoundaries_onMDS_randomforest_proximitymatrix_features.png)
### Project Description
Classification of elder fallers who have self reported falls during last year versus healthy elders who have not fallen. Predictors are some clinical questionnaires and tests as well as some new features constructed with accelerometer data from 1 minute self paced walking. Dataset consists of 71 subjects and was found on Long Term Movement Monitoring Database in physionet.org.
### Project's main result
78% mean accuracy score on 5fold crossvalidation 
### Frameworks used
Python, Google Colab
### Some of the python libraries used
Numpy, Pandas, Matplotplib, Sklearn

## **2. Parkinson Classification**
![alt text](Parkinson_MLmodel_Scores_5cv.png)
### Project Description
Classification of Parkinson from healthy individuals based on features constructed from acceleration data, extracted during 2 minutes of self paced waling. Some of the new features constructed are Hurst exponent from detrended fluctuation analysis and sample entropy on stride time intervals. Limitations on using these features in the current project are mentioned in the Read.me file in github repository. Dataset consists of 93 and 73 parkinson and healthy subjects respectively, and was found on Gait in Parkinson's Disease database at physionet.org.
### Project's main result
73% mean accuracy score on 5fold crossvalidation
### Frameworks used
Python, Google Colab
### Some of the python libraries used
Numpy, Pandas, Seaborn, Sklearn

## **3. Greek Football League Analysis 2020-2021**
![alt text](perc_pred_wins_vs_perc_true_wins.png)
### Project Description
The aim of this project was to find bookmaker's accuracy and provide useful insights from statistics of the whole league as well as per individual team. Data were found on football-data.uk.com.
### Project's main results
Bookmaker predicted 82.4% of home wins right, 48.1% of away wins right and just 1.4% of draws right. The three most important match statistics, associated with win in the league were total number of shots on target, total number of shots and number of fouls.
### Frameworks used
Python, Google Colab
### Some of the python libraries used
Numpy, Pandas, Matplotlib, Sklearn

## **4. Injury Prediction on Mid-Long Distance Runners**
![alt text](WeightedXGBoost_Metrics_TestSet.png)
### Project Description
The aim of this project was to predict overused injuries in mid-long distance runners before they happen based on a number of features regarding external load, subjective estimates of exertion etc. Each instance (healthy day or injury day) contains variables containing information about the previous 7 days before that instance. Target variable (injury or not) was heavily imbalanced. Data were found on a github repository of [josedv82](https://github.com/josedv82/public_sport_science_datasets), containing open source datasets relative to sports science. More information can be found on the original source [https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/UWU9PV](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/UWU9PV).
### Project's main result
Best model resulted in 70% Area Under Curve Score, 76% Sensitivity and 60% Specificity
### Frameworks used
Python, Google Colab
### Some of the python libraries used
Numpy, Pandas, Sklearn, imbalanced, Tensorflow

# *Education*
* Bachelor in Physiotherapy, Alexander Technological Educational Institute of Thessaloniki
* Master in Sport and Health, Aristotle University of Thessaloniki

# *Scientific Publications*
Vizirgianakis S, Amiridis IG, Mademli L, Tsiouri C, Hatzitaki V. [Posture dependent ankle and foot muscle responses evoked by Achilles' tendon vibration.](https://www.sciencedirect.com/science/article/abs/pii/S0304394021003736?via%3Dihub) Neurosci Lett. 2021 Aug 10;759:135995. doi: 10.1016/j.neulet.2021.135995. Epub 2021 May 28. PMID: 34058294.
