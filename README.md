# Data Internship Code Challenge - 22nd May 2018
## Due: 23rd 9:00am May or Earlier


## Task 1
###### If you copy paste a set of steps more than 3 times, it’s time to write a what?
It is time to write a function. It enables code reuse, preventing code redundancy.

## Task 2
###### Given a dataset on any one of Africa’s Talking products: Voice, SMS, Payments and USSD. Discuss the steps you would take to analyse the data to reach a conclusion.
Finding and understanding a problem to solve and the business need is the first step. This will drive my analysis and shape my project.  

After this, obtaining the data follows. Connecting to a database; plugging into a data lake or store or using APIs to source payments data for instance are some of the ways to collect relevant data.
 
The data might be messy- missing values or nconsistencies- and to get quality results, cleaning has to be done. This involves formatting the data to a prefferable format, defining extent and sample of data to use and fixing or removal of missing data. 

Next comes undrstanding the data: Exploration. Here, visualisation of the various fields and digging into the various features by clustering to get an insight on how the data looks like and further extract features from the data.
 
After this, working with machine learning algorithms to model the data and get predictive and interpretive results begins.
Depending on the problem and the behaviour of the data, choose an algorithm which has a good F-score and one that generalises well. 

These results are then interpreted and used to bulid new solutions or improve on existing ones.

## Task 3
###### Give an example explaining how K-means clustering works.
K-Means algorithm is a clustering algorithm. It takes unlabelled datasets and cluster them in groups. It does so by first initialising points(centroids)- this is done randomly and the number of centroids depend on the number of groups the data will be clustered into. The algorithm iterates through two steps: assigning clusters to the examples then moving the centroid position. Basically, the algorithm goes through the data set and assigns each data point to one of the centroids depending the one it is closest to; then each of the centroids are moved to the average position of the data points assigned to it. These too steps are repeated until the centroids cannot move any further: that they are in their assigned data points' average. At this point, the algorithm will have converged and thus have found the clusters in the data.

## Task 5
###### Suppose there’s a contest in which people each pick a number between 0 to 100. The winner of this contest will be the person who picks the number closest to ⅕ of the average. What’s the winning number.
100 cannot be the winning number. Given that 1/5 of the average cannot be 100. A rational player will not choose a number more than 20. If all players base their choice on such knowledge and assume all other players do so too, then the winning number will be no greater that 4 as the 1/5 of the average will be 4. This continous assumption will boil down to the most rational number chosen by all players to be zero. This is however, not realistic as not every player might base their answer on "rationality". The winning number is hard to infer. 

