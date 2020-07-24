# sparkify-churn-prediction
## Project Description & Motivation
There are many services which can meet our wants to listen to music. Recently, music streaming services, such as Spotify, Apple music, and Youtube Music, are being the first option to meet the wants to play songs over CD’s, or mp3 players.  
In music streaming business, customer retention is crucial to earn higher profit. Predicting customers’ cancellation of service and preventing them from churn is a key to success in the industry.   
Sparkify is a fictional music app provided by Udacity for data capstone project. To indirectly experience the churn project in the music streaming industry, I tackled this data science project.
  
  
## Contained Files
1. **data**  
In `data` folder, `medium-sparkify-event-data.json` file is stored. In the dataset, user logs in Sparkify app is contained.  
2. **code**  
In `code` folder, `sparkify-churn-prediction.ipyng` file is stored. The file conains code that analyzes user log, and predicts churn with various ML models.  
3. **code-preparation**
In `code-preparation` folder, the basic pyspark codes that can wrangle data set and apply ML models are included.  
  
  
## Libraries Used
The code can be executed in local machine, but research can be done faster in IBM Watson Studio. I used IBM Watson with default Spark 2.4 & Python 3.6.  
  - pyspark.sql, pyspark.ml
  - pandas
  - numpy
  - matplotlib
  
  
## Result Summary
In this research, 4 classifiers are tested to predict churn. Naive Bayes, and Linear Support Vector Machine performed well, recording 81% of F1 score. They outperformed the other two classifiers, Logistic Regression, and Gradient Boosted Tree, with F1 score of 78%. In my opinion, this is due to the fact that increasing variance deteriorates the performance more than bias does, making simple models perform better than variant models.  
  
  
## Acknowledgements
The data set for this project is provided by Udacity for DSND data capstone project. If possible, conduct research in cloud, such as AWS or IBM Watson Studio. For reading detailed research, follow the blog post link below:  
https://medium.com/@lim.andrew1/churn-prediction-8707395ddb3b
