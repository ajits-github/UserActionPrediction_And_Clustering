# UserActionPrediction_And_Clustering

Predict the actions based on the user behavior for the given URL

* The accompanying data set consists of user sessions in an anonymized web app. In particular, it contains actions that these users take on a given URL at a given date and time.

Below are the tasks covered in the notebook:

* Exploration of the data and extensive observations
* Creating user segments (clusters) based on their activity
  * What kind of cleaning is needed to be done?
  * What features can be created for this segmentation?
 
* Visualize the clusters
* Analyze URL structure
* Patterns in sessions/paths
* Some predictive modeling

----------------------------------------------------------------------------------
A sample image from the outputs displaying the user activity heatmap for the purpose of **Feature Selection** which plays a big role here:
* The heatmap allows for the identification of any recurring patterns or trends in user activity over the course of a week.
* From the heatmap, we can identify periods of high activity as clusters of darker colors, indicating peak times when users are most active. Conversely, lighter colors represent periods of low activity or off-peak times.
* For example, it can be seen that 4th (Thursday) day of the week is the busiest day whereas the time between 6:00 and 16:00 seems to be the most used hours during the day which can be attributed to general office timings.
  
![User_activity_heatmap](https://github.com/ajits-github/UserActionPrediction_And_Clustering/assets/71327507/2768c3fd-927e-4a8b-b3dd-82be2e8ae9d9)
