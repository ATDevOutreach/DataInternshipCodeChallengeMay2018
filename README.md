# Data Internship Code Challenge - 22nd May 2018
## Due: 23rd 9:00am May or Earlier


##### There are six tasks in this challenge, complete 1, 2 and 3 and write your answers in a ReadMe. Then choose between 4, 5, 6 and complete one of those. The submission instructions are specified at the bottom of the challenge page.

## Task 1
###### If you copy paste a set of steps more than 3 times, it’s time to write a what?
##### A: Function - to bundle the set of steps


## Task 2
###### Given a dataset on any one of Africa’s Talking products: Voice, SMS, Payments and USSD. Discuss the steps you would take to analyse the data to reach a conclusion.
##### A: Data Analysis steps:
###### 1. Fomulate a question
>    Step one would be to ask why I want to do this data analysis. Is there a specific question for the analyis? Is it a business problem we are trying to solve therefore hoping that data analysis would reveal more insight, or is it a general hunt patterns and trends in the dataset.
    Example analysis question: AT has high SMS traffic at certain periods of the month, especially end of month. Determine and confirm correlation of sms traffic and the monthly calendar.
###### 2. Explore the data
>    Step two is extensively check the data noting aspects of the data like its format and quality (supposing I have an indicator like the minimum data that would fully form a single data point).
    In the example case above, Id check the frequency of the data. Was it recorded daily as a count of SMSes sent and received in a day, or is the data a huge store of each individual text sent. Are there timestamps in the data, are all data points timestamped. The data given, does it cover our interest period of study, say, the last six months... is the data streaming realtime from an API endpoint
###### 3. Pre-process the data
>    I would then preprocess the data, converting any formats that I need to and maybe filtering out data points that I have clearly determined to be outliers.
    In the cexample case, assuming the data is a SMSes transacted in a day, and the dataset is a snapshot of the last one year. If I am to perform an analysis for the last six months only, I would filter the data extracting just the last six months.
###### 4. Perform analysis and build models
>    Next, I would perform an analysis, based on the preprocessed data and the question of analysis. In a machine learning case, I would formulate models and improve upon them based on the results, iteratively. A model framed with the analysis question, would form my criteria for success.
    In my analysis case, I may plot the data points for every subsequent months.
    This can be done using weekly averages against the weeks of the month for all the seix months, or for every single day for all the six months.
###### 5. Assess the results
>    I would then review results from the analysis, discuss them and test them against my hypothesis.
    Humps and dips in SMS counts peaking at the end of a given month and diping off with the transition into a new month would confrm the end-month hypothesis. The results, could otherwise show various other patterns and correlations between SMS traffic and the time of the month. These assesments, would form the basis of my conclusion.
    In this case, the existence of such a pattern would be half the data analysis, not answering the question of why it actually occurs.

## Task 3
###### Give an example explaining how K-means clustering works.
##### A: K-Means Clustering. Image classification example
###### This is an example of K-Means clustering in land use classification of a satellite image
###### Each pixel in a satellite image has a digital number between 0 and 255 (8-bit color). If from visual inspection the image appears to have 12 land use classes with examples of urban areas, forests, water and possibly many types of farmlands, an unsupervised classification would work to assign every pixel in the image to a land use class
##### 1. Data assignment
    start with K = 12
###### On the first run, the clustering algorithm will slice up the value range of `0 - 255` into `12` centroids, and group each pixel around a centroid with value closest to it. This is the data assignment step based on squared euclidian distance
##### 2. Update centroids
###### The algorithm then averages the pixel values of all pixels in each cluster, and updates the centroids of teh cluster to be that average
##### 3. Check a baseline
###### A stopping condition is checked. If this baseline has not been met, step 1. of data assignment is done on the clusters and then step 2 followed by 3. Stopping conditions could be the number of iterations, as this algorithm is assured to produce results even with one pass.
###### If the stopping condition is met, the algorithm returns the clusters generated. In this case, 12 land use classes.
###### Manual labeling of the classes can then be done

## Task 4
###### Given a Gigabyte of weather data, how would you go about calculating the mean temperature of a particular place and plotting a graph to show change in variation of daily temperature.

## Task 5
###### Suppose there’s a contest in which people each pick a number between 0 to 100. The winner of this contest will be the person who picks the number closest to ⅕ of the average. What’s the winning number.

##### A: Number Lottery
>    People : 0 to 100, assume maximum: n = 101 people

>    1/5 * average => 0.2 * [ (n/2) * (n+1) ] / n

>    0.2 * [ (101 / 2 ) * 102] / 101 = 10.2

####> Winning number is 10


## Task 6
###### Uber recently released data that you can find on uber movement website. Download and analyse interesting data that you find. State the insights that you got from analysing the data. Please send us your work as notebook format you prefer.

<br><br>

## How to submit
1. Check out the format for submitting your code [here](http://atdevoutreach.viewdocs.io/DataInternshipCodeChallengeMay2018/CodeChallengeSteps/)

2.  Make sure when creating a branch to use your correct phone Number, as this is what we will use to get back to you.

> NB: As a branch-name you can also use your email.
> See you on the other side, and best of luck!


## Join Slack
In case you have any questions, join our Slack [here](https://slackin-africastalking.now.sh/) and join the #internship-challenge channel.

## About Africa's Talking Code Challenges
Please read the overview [here.](http://atdevoutreach.viewdocs.io/DataInternshipCodeChallengeMay2018/)
