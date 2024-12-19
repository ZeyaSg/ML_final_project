# ML_final_project
475/675 final project\
File Descriptions and Instructions to Run:\
Phones 2024 is downloaded in the home directory. 
All inermediate data files saved and loaded are in the home directory. For zip files please unzip them first. For filtered_phone_w_reviews.npy, the file is too large to be uploaded, so please run ML_final_project_data_filtering_&_matching.ipynb to regenerate the data. Please run the notebook in the home directory to access the files.
File descriptions:
1. ML_final_project_data_filtering_&_matching.ipynb: This loads the Amazon Review dataset, and apply $50 filter. It also takes in the BERT-labelled data and matches it to reviews and later to phone specs.
2. Data_Manual_Label_Finalized.ipynb This file is for manually labeling the unlabeled Amazon Review dataset. It generates some .npy that will be used in later files by data splitting. \
3. Model_Choose_Cross_Validation_Finalized.ipynb This file runs cross-validation for BERT and RoBERTa.\
4. Data_Labeling_BERT_Finalized.ipynb This file uses BERT and manually labeled data to classify all the Amazon Review Data.\
5. Clustering_with_reviews.ipnyb This file performs clustering and generates the corresponding recommender based on processed Amazon Reviews 2023 dataset.\
6. Clustering_with_specs.ipnyb This file performs clustering and generates the corresponding recommender based on the processed Phones 2024 dataset.\
7. Clustering_w_matched_phones.ipnyb This file performs clustering on the matched dataset. 
