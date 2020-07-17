## Objective
The objective of this project was to find out how best to segment customers of a certain auto insurance company. This segmentation is intended to provide opportunity for targeted advertisements, packages or deals based on the most efficient demographic splitting.

## Universe
In total, the data consisted of 9134 customers which with a value or descriptor in the 23 variable database. These variables consisted of location, policy and vehicle information, as well as personal info like marital, employment and education status and Customer Lifetime Value. 

## Modelling
For this analysis, a collection of different clustering models were attempted. I worked with KMeans and KModes, DBSCAN, PCA and Hierarchichal clustering. 
* KMeans was not found to be very efficient, as well as KModes. 
* Since there was a lot of similarity in the data, PCA was found to be relatively useless.
* DBSCAN was slightly worse than KMeans, but was still not scoring high.
* Hierarchical clustering was by far the best, with a silhouette score of about 0.74. 

## Outcomes/Conclusions
Ultimately, it was found that with Hierarchical clustering, the best segmentation was found with personal information - employment and marital status. These provided a great way to characterize the employee base. A concise breakdown can be found in the presentation deck. 
