### **Data Wrangling**
 Data wrangling is the process of gathering your data, assessing its quality and structure, and cleaning it before you do things like analysis, visualization, or build predictive models using machine learning.
 
 Data wrangling consist of three steps namely;
 1. Data Gathering
 2. Data Assessment
 3. Data cleaning
 
#### **Data Gathering**
I acquired the data from three different sources;
- The first data was twitter_archive_enhanced.csv which I manually downloaded from Udacity servers, then I upload it and read the data into a pandas DataFrame. 
- The second data was image_predictions.tsv was also hosted on Udacity’s server. I downloaded it programmatically using the Requests library.
- The last data was acquired from Twitter API. I used the tweet IDs from the WeRateDogs twitter_archive_enhanced.csv, I then queried the Twitter API for each tweet’s JSON data using Python’s Tweepy library and store each
tweet’s entire set of JSON data in a file called tweet_json.txt file.

#### **Data Assessment**
I used visual and programmatical assessment to assess the data. DataFrame inspection was done using Pandas inspection along with data assessment in Excel spreadsheet.
Programmatically, I inspected the data using different Python methods and functions. 
The data was assessed for quality and tidiness.
#### Data Cleaning
Issues found during the assessment stage were cleaned using different Python method. 

Once the data was clean, several analysis were conducted and visualizations plotted to refect the finding.


