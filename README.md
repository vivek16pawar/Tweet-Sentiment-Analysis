<p align="center"> 
<img src="Images/580b57fcd9996e24bc43c53e.png" alt="netflix-logo-png-2574.png" width="80px" height="80px">
</p>
<h1 align="center">Tweet Sentiment Analysis  </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p align="center"> 
  <img src="Images/free-twitter-sentiment-analysis-tools-update-tile.png" alt="netflix-logo-png-2574.png" width="800px" height="500px">
</p>

<p align="center"> 
  
</p>

<p>We have build system to check the sentiment of the user based on the tweets, it is categorized into positive sentiments or negative sentiment. </p>

<h2> :floppy_disk: Project Files Description</h2>

<h4>Executable Files:</h4>
<ul>
  <li><b>Coronavirus_tweet_sentiment_analysis.ipynb</b> - Includes all functions required for classification operations.</li>
</ul>

<h4>Output:</h4>
<ul>
  <li><b>Google Colab</b> - All the outputs are visible in the provided colab notebook.
</ul>

<h4>Data Source:</h4>
<ul>
  <li><b>Dataset</b> - https://www.kaggle.com/datasets/lopezbec/covid19-tweets-dataset</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Business Problem And Objective </h2>

<p

  Sentiment analysis refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.

Therefore we need to develop an Automated Machine Learning Sentiment Analysis Model in order to compute the customer perception. Due to the presence of non-useful characters (collectively termed as the noise) along with useful data, it becomes difficult to implement models on them.
   
   

</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: About Dataset </h2>

<p

- Location : Location from where tweets are done
- Tweet At : Date and time of the tweet
- Original Tweet : Context of the tweet
- Label : Sentiment of the tweet
   

</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📙: Findings and Results </h2>

<p

Original Dataset contains 6 columns and 41157 rows.
Location column contains null values. So, we have dropped the null values.
And we added a new column "clean_tweets" after cleaning the tweets.
After dropping and adding a new column, now we have 7 columns and 32567 rows.
In order to analyze the data we required only two columns "OriginalTweet" and "Sentiment".
The columns such as "UserName" and "ScreenName" does not give any meaningful insights for our analysis.
There are five types of sentiments - Extremely Positive, Positive, Extremely Negative, Negative and Neutral.
We have renamed the Extremely Positive and Extremely Negative sentiments to Positive and Negative respectively. And we are left with three types of sentiments - Positive, Negative and Neutral.
The pie chart shows the proportion of sentiments.
Bar plot for unique values shows us the number of unique values in each column.
The graphical representation of top 10 locations shows us that most of the tweets came from London followed by United States.
   
   
- For multiclass classification, the best model for this dataset would be Logistic Regression

- For binary classification, the best model for this dataset would be Stochastic Gradient Descent.
   

</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: About Dataset </h2>

<p

- Location : Location from where tweets are done
- Tweet At : Date and time of the tweet
- Original Tweet : Context of the tweet
- Label : Sentiment of the tweet
   

</p>
                  
                  
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the colab notebook is as follows:</p>
<p><b>1) Coronavirus_tweet_sentiment_analysis.ipynb</b></p>
<p>First, click on the open in colab button present on the top center of the notebook.</p>
<p><b>2) Kaggle Dataset</b></p>
<p>Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.</p>
<p><b>3) Cell Path</b></p>
<p>Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Vivek Pawar | Data Scientist | Machine Learning Engineer 

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://https://www.linkedin.com/in/vivek-pawar-data/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vivek16pawar)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@vivekpawar.data)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/18h-_iI4MkUf1FLnx-By5vAoZawhXdUo0/view?usp=sharing)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

