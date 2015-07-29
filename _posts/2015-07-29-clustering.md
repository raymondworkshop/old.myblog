---
layout: post
title: "Clustering"
date: 2015-07-29
comments: true
categories: [technology, datamining]
---
### clustering : divide a set of objects into meaningful groups

#### centroid-based partitioning
   * Objects in the same cluster should be similar to each other, while in different clusters should be dissimilar.

	  
      * k-center: find the k center set with the **smallest radius r* **
	   - NP-hard
	   - an optimal k-circle: a 2-approximate k circle cover
		   + returning a k-center set with radius at most 2r*
		   
		   + choose **a random point** firstly, then choose the MAX distance to the points
		  
   * k-mean
	   - **k random points** as the initial centroid, form k clusters by assigning all points to the closest centroid
		   + each point is chosen as the centroid with a probability proportional to (D(p)^2)
		   + if 100%, that's k-center
		 
	   - k-means alg always terminates
		   +  only a finite number of centroid sets that can possibily be produced at the end of each round
		   +  after each round, the cost (the distance) of the centroid set is strictly lower than that of the old centroid set
		   
	   - the accuracy guarantee
		   +   k-seeding : TODO
		       the seed choice (David Arthur, Sergei Vassilvitskii: k-means++: the advantages of careful seeding. SODA 2007: 1027-1035.)
		 
		 - the limitation of k-mean
		   + differing sizes, differing density,  Non-globular shapes
		  
#### Hierarchical Methods 
  * Why 
	  - when a clustering needs, different users can explore the hierarchy to obtain **various** clustering results efficiently
	  
  * How
      - the agglomerative method: merge the most similar two clusters until only one cluster is left
	  
  * Given a dendrogram (the merging history), we can obtain k clusters
	   - the alg:
	       + **binary search tree (BST)** is used to store the distances of all pairs of the current clusters
	       
	   - TODO		   
	    
	  
	  
	  
