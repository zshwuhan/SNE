This is a guide for data format.
We use three files in total.

attr_info.txt  
   In this file, each line corresponds to a user. The first entry is user id. Other entries indicate attributes.

doublelink.edgelist  
  This file contains links for training our model. 
  
test_pairs.txt  
  This file contains a list of node pairs. The first two column are node ids. The entries in third column indicate the existance of links. 0 means that there is no link between this pair of nodes. 1 means there is a link between nthe pair of nodes.
