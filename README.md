# K-Means_Clustering
This repository stores implementation to K Means Clustering

K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science. 


K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on.

The algorithm takes the unlabeled dataset as input, divides the dataset into k-number of clusters, and repeats the process until it does not find the best clusters. The value of k should be predetermined in this algorithm.

The k-means clustering algorithm mainly performs two tasks:

Determines the best value for K center points or centroids by an iterative process.
Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster.
Hence each cluster has datapoints with some commonalities, and it is away from other clusters.



        For this project I have attempt to use KMeans Clustering to cluster Universities into to two groups, Private and Public.

          It is very important to note, we actually have the labels for this data set, but I have NOT use them for the KMeans clustering algorithm, since that is an unsupervised learning algorithm.

          When using the Kmeans algorithm under normal circumstances, it is because we don't have labels. In this case i have used the labels to try to get an idea of how well the algorithm performed, but you won't usually do this for Kmeans, so the classification report and confusion matrix at the end of this project, don't truly make sense in a real world setting!.

          The Data
          We will use a data frame with 777 observations on the following 18 variables.

          Private A factor with levels No and Yes indicating private or public university
          Apps Number of applications received
          Accept Number of applications accepted
          Enroll Number of new students enrolled
          Top10perc Pct. new students from top 10% of H.S. class
          Top25perc Pct. new students from top 25% of H.S. class
          F.Undergrad Number of fulltime undergraduates
          P.Undergrad Number of parttime undergraduates
          Outstate Out-of-state tuition
          Room.Board Room and board costs
          Books Estimated book costs
          Personal Estimated personal spending
          PhD Pct. of faculty with Ph.D.’s
          Terminal Pct. of faculty with terminal degree
          S.F.Ratio Student/faculty ratio
          perc.alumni Pct. alumni who donate
          Expend Instructional expenditure per student
          Grad.Rate Graduation rate
          
          
          
          There is no perfect way to evaluate clustering if you don't have the labels, however since in this project, I do have the labels, so i have taken  the advantage of this to evaluate our clusters, keep in mind, you usually won't have this luxury in the real world.
