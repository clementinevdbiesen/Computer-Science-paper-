# Computer-Science-paper-
This code contains a method for scalable duplicate detection of product data on webhops. It involves single linkage clustering and LSH to improve the efficiency of duplicate detection in case there are many possible comparisons. The code first imports the data from a JSON file, and then cleans all the data so that it can be used in the method. After this, the functions that will be used are defined. These include functions to make the binary and signature matrix used in LSH. Then the main functions for the output of the code are defined, which is a function that makes the candidate pairs from LSH, and a function that can use these pairs to output F1 and F1* scores. After this the clustering method functions are defined, including Jaccard similarity, dissimilarity matrix and clustering method, to further reduce the candidate pairs. Then the results are evaluated over different number of bands in the LSH method, and also over 5 bootstraps so that the results are more robust. Plots are also made.  
