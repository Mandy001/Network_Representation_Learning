# A Study of Neural Networks for Network Representation
Network structure is very common in our daily applications, especially in the systems involving users. Due to the particularity of the network structure, it is challenging to deal with network relationships (finding suitable network structure representations), especially for large network representation, it may require much more computational complexity. The purpose of the project is to explore and modify the state-of-the-art network embedding methods to do some specific tasks (in this project, I will do the node classification task).I have implemented a recently proposed method called DNGR to learn a effiective low dimensional representation of the Wiki dataset, and used different evaluation criterion to assess the classification performances. Finally, I used the t-distributed stochastic neighbor embedding (t-SNE) method to gain an visualization of the classification results. 

## About the dataset
I choose the Wiki dataset provided by openNE toolkit [https://github.com/thunlp/OpenNE](https://github.com/thunlp/OpenNE) for node classification task, which contains 2405 web pages from 19 categories and 17981 links among them. The Wiki dataset was composed by two files: "Wiki_edgelist.txt" and "Wiki_category.txt". The "Wiki_edgelist.txt" file stores the relationship graph between different nodes, which is a 2045 by 2045 adjacent matrix. The "Wiki_category.txt" file stores the actual classification of these nodes, which is used to evaluate the performance of my model in node classification task.
