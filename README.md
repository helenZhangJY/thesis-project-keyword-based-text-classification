# Keyword-based text classification method
Author: Jingyue Zhang

This repository is part of the 2022 Mater of Text mining thesis "Mapping text to learning objectives: A keyword-based text classification method" by Jingyue Zhang. This thesis project was part of an internship offered by EDIA and was supervised by Hennie van der Vliet, Pia Sommerauer, Mark Breuker and Isa Maks.

# Project structure

```
thesis-project
└───data
│       │   dev_data.csv 
│       │   test_data.csv
│       │   LO_picklefile
│       │   stopwords
└───results
│       │   evaluation.ipynb 
└───code
│   │   crawl_dev_data.ipynb 
│   │   basic_statistics.ipynb
│   │   run_dev_bl.ipynb
│   │   run_dev_w2v.ipynb
│   │   run_test_bl.ipynb
│   │   run_test_w2v.ipynb
└───LICENSE
└───README.md
```

## Thesis report
When the thesis report is officially published on the CLTL website, the link will be shared here afterwards.

## Data
In the 'Data' folder you can find two csv files 'dev_data.csv' and 'test_data.csv' with all the gold labels and assigned labels generated by baseline system, word2vec system and EDIA's system. 

There are two sub folders: stopwords folder contain English stopwords list and Dutch stopwords list. LO_picklefile folders contain learning objectives pickle files for GCSE Combined Science and SURF Lexical Information Literacy (Vocabulaire Informatievaardigheid).



Gathering and annotating the data was part of this thesis project. The provided excel file contains the 'most correct' labels of my agreement study. More information on this agreement study can be found in Chapter 3 of the thesis report in the file 'Eva_Zegelaar_Thesis_Report.pdf'.

## Code
In this folder you can find 6 jupyter notebook files, in each file you can find the code and outcomes of the code.
- cwarl_dev_dataset.ipynb: generate development dataset.
- basic_statistics.ipynb: generate basic statistics on development data and test data.
- run_dev_bl.ipynb: clean developemnt data, extract keywords from development data, generate labels based on baseline system.
- run_dev_w2v.ipynb: clean developemnt data, extract keywords from development data, generate labels based on word2vec system.
- run_test_bl.ipynb: clean test data, extract keywords from test data, generate labels based on baseline system.
- run_tsst_w2v.ipynb: clean test data, extract keywords from test data, generate labels based on word2vec system.

## Resources
Word Embeddings:
Due to the large size, the open-source pre-trained Englsih and Dutch word embeddings were not uploaded here. However, to be able to run the word2vec system, you need those word embeddings. These can be downloaded from the following page: http://vectors.nlpl.eu/repository/

## References
Keywords Extraction Using TF-IDF Method https://www.kaggle.com/code/rowhitswami/keywords-extraction-using-tf-idf-method/notebook
Cosine Similarity between two sets of vectors? https://math.stackexchange.com/questions/1122423/cosine-similarity-between-two-sets-of-vectors





