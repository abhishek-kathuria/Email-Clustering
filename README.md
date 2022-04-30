# Evaluating Cohesion Score with Email Clustering 
This respository contains the implementation of my research paper titled "Evaluating Cohesion Score with Email Clustering" which has been published in "Proceeding of first International Conference on Computing, Communication and Cyber-Security (IC4S-2019), pp 107-119" which is a part of the "Lecture Notes in Network and System" Jorunal.

I presented this paper as a first author at the International Conference on Computing, Communications and Cyber-Security (IC4S-2019) which was held in the Institute of Engineering and Technology, Chandigarh. 
I was honoured with the BEST PAPER AWARD for the presentation of my paper as the first author by Prof.(Dr.) Neeraj Kumar (Professor, CSE Dept., Thapar University).

## Requirements
1. Anaconda
2. Python 3.6
3. Numpy 
4. Pandas
5. sklearn
6. nltk
7. matplotlib
You can either run the code on python 3.6 or on the kaggle kernel GPU.

## Usage
1. Clone this repository : git clone 
2. Directly run the "EmailClustering.ipynb" file

## Abstract 
An email has become one of the prime ways of communication for individuals or organizations and has emerged as an important research field to categorize emails and enable users for easy data segregation, topic modeling, spam detection, network analysis for investigative and analytical purposes. The paper aims to cluster the emails comprising of 500,000 emails taken from the Enron email dataset which was obtained by the Federal Energy Regulatory Commission during its investigation of Enron’s collapse, based on the relevance of the words to the whole corpus. The proposed algorithm calculates the cohesion score of each cluster using intra-cluster similarity. This paper implements two unsupervised clustering algorithms for the email clustering process, namely k-means and hierarchical clustering and evaluates the cosine similarity of all the words from each cluster to evaluate the semantic similarity pervading through each cluster. The emails were clustered into three groups and the cohesion score was obtained for each cluster which measured the intra-cluster similarity. The proposed method helped in the computation of the score distribution among the clusters, as well as the intra-cluster similarity. Cluster 1 obtained the highest cohesion score among all the three clusters by attaining the cohesion score 0.1655 while using the k-means algorithm and the cohesion score of 0.2513 while using the hierarchical clustering algorithm.

## Citation 
If you find this code useful for your research, please consider citing my paper:

@inproceedings{kathuria2020evaluating,
  title={Evaluating Cohesion Score with Email Clustering},
  author={Kathuria, Abhishek and Mukhopadhyay, Devarshi and Thakur, Narina},
  booktitle={Proceedings of First International Conference on Computing, Communications, and Cyber-Security (IC4S 2019)},
  pages={107--119},
  year={2020},
  organization={Springer}
  }

