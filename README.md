### Clustering using Kidney Inspired Algorithm

The objective is to cluster data (I have used 3 datasets - Iris, Ecoli, New-Thyroid) using the Kidney Inspired Algorithm as an optimization function (to improve cluster centroids). Here clusters are represented as centroid based chromosomes, where each chromosome represents k cluster centres. Till here has been implemented in *kiaclustering_final.py*
In *kiakmeans.py*, a fraction of the solutes have been initialized by running KMeans algorithm on the input data, to obtain better clusters.
At the end, both *kiaclustering_final.py* and *kiakmeans.py* write the results (Accuracy, DBIndex, Silhouette Index, Entropy, SSE), along with the information of the clusters assigned to all the data points into a file *resultXX.csv*, where XX is the number of iterations for which the algorithm has been run.

### Instructions to run
The following parameters need to be updated before running the file - 

>1. Select dataset and uncomment the code for pre-processing that dataset
>2. change the value of *k* as the number of clusters required
>3. Change the value of *numIter* as the number of iterations for which the code will be executed. For best results, set numIter>=10000

