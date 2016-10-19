# SignatureFinder

SignatureFinder builds the gene signature, using statistical methods and knowledge contained in the Gene Ontology.

First, using the Kruskal-Wallis test, selects genes which most differentiate specific types of cancer. Then, referring to the characteristic features downloaded from the Gene Ontology, selects genes with similar functions as the group selected in the first step. Then add them to the signature.

Another adventage of the package is to create SVM classifier or random forests classifier which are based on the genes from the signature. Therefore the result of the package is a vector of gene signature and a tool which allows to classify new cell samples from patients to a particular type of cancer.

#Install

