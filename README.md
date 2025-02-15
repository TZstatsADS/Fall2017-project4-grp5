# Project 4: Collaborative Filtering

### [Project Description](doc/project4_desc.md)
![screenshot](figs/friendship_social_network.jpg)

Term: Fall 2017


+ Team 5
+ Project title: Collaborative Filtering


+ Team members
	+ Gao, Xin xg2249@columbia.edu
	+ Hao, Shuyao sh3565@columbia.edu
	+ Li, Peter pwl2107@columbia.edu
	+ Qiu, Peilin pq2128@columbia.edu
	+ Tan, Chaoyue ct2774@columbia.edu


+ Project summary: 
In this project, we implemented two algorithms: memory-based algorithm, including Similarity Weight, Selecting Neighbours and Rating Normalization and model-based algorithm, including Cluster Models to conduct Collaborative Filtering. And we used two datasets, Anonymous Microsoft Web Data and EachMovie Dataset to evaluate and compare a pair of algorithms for collaborative ﬁltering (CF). For evaluation part, compare the performance for these diﬀerent algorithms and component combinations using  ranked scoring for dataset 1 and mean absolute error (MAE) and ROC sensitivity for dataset 2.


+ Project details:
In the memory-based algorithm:
First, we computed different similarity weights. Then, we selected best-n neighbors based on their weights. Last, we predicted ratings using z-score.
In the model-based algorithm, we used cluster model to do Collaborative Filtering.

+ Results:
We found memory-based model with pearson weight + significance weighting + best-n + z-score produced the highest R-score. 

![screenshot](figs/comparison.png)

**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. And the most important thing is all of our members worked very hard to complete our project.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
