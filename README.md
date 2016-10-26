# SNE
Social Network Embedding framework (SNE)

The codes implement the SNE method, which maps the discrete social network data into a continuous low-dimensional vector space. SNE learns representations for social actors (i.e., nodes) by preserving both the structural proximity and attribute proximity. 

The code is developed in Python, based on tensorflow (https://github.com/tensorflow/tensorflow)

A Runner is provide in 'SNE_runner.py', which runs the SNE method and gives evaluation results using test data provided.

About the datasets: There are two types of networked datasets in the paper, facebook friendship networks and citation networks. Those two datasets are both publicly accessible. Thus we give an example one (UNC) here. The dataset contains 3 files:

1. attr_info.txt : In this file, each line corresponds to a user. The first entry is user id. Other entries indicate attributes.


2. doublelink.edgelist : This file contains links for training our model.

3. test_pairs.txt: This file contains a list of node pairs. The first two column are node ids. The entries in third column indicate the existance of links. 0 means that there is no link between this pair of nodes. 1 means there is a link between nthe pair of nodes.
