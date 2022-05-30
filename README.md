# Module_13_Challenge

## Machine Learning Trading Bot

As a financial advisor of the top five financial advisory firms in the world, I have computer algorithms that can buy and sell faster than human traders. I will be  enhancing the existing trading signals with machine learning algorithms that can adapt to new data.

## Purpose
* The purpose of the analysis is to use machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

## Analysis of Actual Returns vs. Tuned ML Bot Returns
After changing the training window, the model accuracy score, and the cumlative performace of the strategy have improved. 
The accuracy score was at 0.56 
The cumulative performance was at 1.634%. 
![Screenshot 2022-05-29 171645](https://user-images.githubusercontent.com/99453114/170897409-2cfd02ff-efdb-4662-8c31-f6307e46c508.png)

## Analysis of Actual Returns vs. AdaBoost Returns

short_window = 4
long_window = 100
DateOffset = 3 months
The accuracy of the AdaBoost classifier model was in line with the SVC's at 0.55

The AdaBoost Classifier returned an on overall performance of 1.571. The AdaBoost classifier model outperformed the baseline SVC model, returning 1.57 versus 1.52.

It appears that the AdaBoost classifier model is better at predicting the signals for the short-long algorithm with the original parameters than was the SVC model.
Overall, increasing the training window imporved the performance of the model.  

## Conclusions

The Adaboost classifier is likely a better fit for the long-short algorithm trading.

## Technologies

Python, Pandas Library, Anaconda Jupyter Lab, Pathlib Library, tensorflow, sklearn.


## Installation Guide
•	Install Python (Refer python installation guide) NumPy, PathLib, pandas, tensorflow and sklearn.
•	Install Anaconda
•	Install Jupiter Lab
Install required libraries such as fbprophet 
•	checkout git repository https://github.com/Ahmedfadiya/Module_13_Challenge.git
•	navigate to the folder through Jupyter Lab


## Usage


1.	Navigate ..\Challenge_Folder\Module_14_Challenge\Starter_Code\machine_learning_trading_bot.ipynb" through Jupyter Lab
2.	run All cells
3.	Models and plots will be displayed inline


## Contributors

Fadiya Ahmed | ahmedfadiya@hotmail.com
---

## License

GPL License
