# Energy-Consumption-Prediction-by-using-Machine-learning-Techniques
--> Downstream of Data Analysis and Machine learning (Time Series Data Analysis)


### About the project abstract:
The maximum Population and Industrial sectors are responsible for huge amount of energy consumption.This research project is aimed to predict the total amount of energy consumption from last 10 years using machine learning techniques. I used supervised learning on “Smart meter in London” from Kaggle. The emphasis of this project is to create regression models which can be further used on downstream of Machine learning task. The secondary aim is to create the visualization and compare which parameters are responsible for maximum energy consumption. For supervised learning, we found the important model parameters like R² (Accuracy of model) and Error types by mathematical equation and apply for model validation for training and testing set.

### About Dataset:
https://www.kaggle.com/datasets/jeanmidev/smart-meters-in-london?select=weather_hourly_darksky.csv


### Context:
Population and industries are continuously increasing in the world day to day. So, the use of energy consumption is continuously increased. When energy usage rises, the climate undergoes numerous changes. The government intends to provide the electricity for smart meters to be installed in every home in England, Wales, and Scotland. There are more than 26 million houses for energy providers to reach, with the objective of putting a smart meter in every home by 2020 [1].
The European Union, which has ordered all member countries to look into smart meters as part of initiatives to modernize our energy supply and combat climate change, is driving this rollout. The British government opted to use smart meters as part of their effort to modernize our aging energy grid after doing preliminary research [1].
The energy usage readings for a sample of 5,567 London Households who participated in the UK Power Networks-led Low Carbon London initiative between November 2011 and February 2014 are contained in this dataset from the London data store. The smart meter data appears to be linked only to electrical energy use [1].


### Content:
For specially this project is possible in two different ways like perform by daily basis as well as hourly basis. Here, I performed my small research project according to daily basis.
Useful files: 
1) https://www.kaggle.com/datasets/jeanmidev/smart-meters-in-london?select=daily_dataset.csv
2) https://www.kaggle.com/datasets/jeanmidev/smart-meters-in-london?select=weather_daily_darksky.csv
3) https://www.kaggle.com/datasets/jeanmidev/smart-meters-in-london?select=uk_bank_holidays.csv

### Acknowledgement:
All the big work of data collection has been done by the UK power networks for the smart meter data.The details related at the acorn group are provided by the CACI. The weather data are from darksky.

### Learning based methods:
1) Supervised Learning 
2) Unsupervised Learning
3) Reinforcement Learning

### Road Map of the project:
1) Data geathering with different multiple files (In our case we have 111 files of daily_dataset_csv and 1 weather_daily_dark_sky)
2) Data Cleaning like remove unnecessary columns, change datatype, date-time extraction, Various kind of suitable encoding methods, use various pandas joins which helpful to merge two different dataframes, fill null data by using various methods etc.
3) Use encoding: One Hot Encoding
4) Visulized the data by various libraries and dashboard 
5) Feature Scaling and feature selection with help of correlation study.
6) After finish the data pre processing, we can try various machine learning models according to case of learning based methods.
7) Model Validation with help of various method, check and defind suitable model with valid model validation
8) Determine the various parameters like model accuracy, Errors, Matrix etc. 
9) Conclusion

### Programming Language and Libraries:
1) Python
2) Sklearn: Pandas, Numpy, Matplotlib, Seaboarn, model_selection
3) Visulization tools: Tableau, Power BI (Optional)

### Existing Research:
1) https://www.kaggle.com/datasets/jeanmidev/smart-meters-london?select=weather_hourly_darksky.csv
2) Anna-Kaarina Seppalä, Stephan Baur, Sudhir Jha, and Emmanuel Benjamin “Simple Regression Model for Energy Demand: Case Study in Rural Areas of Nepal”.
3) M.R. Braun, H. Altan, S.B.M. Beck “Using regression analysis to predict the future energy consumption of a supermarket in the UK”. Journal of Elsevier- Applied Energy.
4) Carlos Peña-Guzmán∗, Juliana Rey “Forecasting residential electric power consumption for Bogotá Colombia using regression models”. Journal of Elsevier- Energy Report volume- 6.
5) Literature review purpose - Western Sydney University
6) Correlation – Wikipedia – Knowledge purpos

