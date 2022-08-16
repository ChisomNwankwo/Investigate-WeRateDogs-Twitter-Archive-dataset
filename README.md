# Investigate-WeRateDogs-Twitter-Archive-dataset

## Project objectives
The project main objectives were:

* Perform data wrangling (gathering, assessing and cleaning) on provided thee sources of data.
* Store, analyze, and visualize the wrangled data.
* Reporting on 1) data wrangling efforts and 2) data analyses and visualizations.

### Step 1: Gathering Data
In this phase, the three pieces of data were gathered and represented as pandas dataframes:

• The Twitter_archived-df(twitter-archiveenhanced.csv). This is a file in hand and was loaded in to the pandas dataframe manuallly.

• The image_df (image-predictions.tsv). This file was be downloaded programmatically using the Requests library from a provided URL.

• Gather each tweet's retweet count and favorite ("like") count at the minimum and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, we queried the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called tweet_json.txt file

### Step 2: Assessing and Cleaning Data
After gathering all three pieces of data, I assessed them visually and programmatically for quality and tidiness issues. While working with data, a number of observations were made. In the below table there are the observations along with actions taken in the Cleaning Step.

### Step 4: Wrangling and Visualization
