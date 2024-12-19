# **ML Final Project**

This repository contains data and code for the final project for the ML 475/675 course. Below are file descriptions and instructions for running the code.

---

## **File Descriptions and Instructions**

### **General Setup**
- **Dataset Location**:
  - `Phones 2024` dataset is downloaded and located in the home directory.
  - All intermediate data files are saved and loaded from the home directory.
  - If you encounter missing intermediate files, either:
    - Run the corresponding data generation code.
    - Contact us to provide the missing files.

- **Special Instructions**:
  - For `.zip` files: Extract them into the home directory before running the code.
  - Always run the Jupyter notebooks from the home directory to ensure proper access to the files.

---

### **File Overview**
Here’s a step-by-step guide to understanding and running the files:

1. **`ML_final_project_data_filtering_&_matching.ipynb`**
   - **Purpose**:
     - Loads the Amazon Reviews dataset.
     - Applies a $50 price filter to the dataset.
     - Matches BERT-labeled data to reviews and, subsequently, to phone specifications.
   - **Output**:
     - A filtered and matched dataset for further analysis.

2. **`Data_Manual_Label_Finalized.ipynb`**
   - **Purpose**:
     - Used for manual labeling of the unlabeled Amazon Reviews dataset.
     - Generates `.npy` files that are used later for data splitting and training.

3. **`Model_Choose_Cross_Validation_Finalized.ipynb`**
   - **Purpose**:
     - Runs cross-validation for classification models (BERT and RoBERTa).
   - **Output**:
     - Evaluates the performance of the models and aids in selecting the best one.

4. **`Data_Labeling_BERT_Finalized.ipynb`**
   - **Purpose**:
     - Uses BERT along with the manually labeled data to classify the entire Amazon Reviews dataset.

5. **`Clustering_with_reviews.ipynb`**
   - **Purpose**:
     - Performs clustering based on the processed `Amazon Reviews 2023` dataset.
     - Generates a recommender system using the clustering results.

6. **`Clustering_with_specs.ipynb`**
   - **Purpose**:
     - Performs clustering based on the processed `Phones 2024` dataset.
     - Generates a recommender system based on phone specifications.

7. **`Clustering_w_matched_phones.ipynb`**
   - **Purpose**:
     - Performs clustering on the matched dataset, which combines reviews and phone specifications.

---

### **Execution Instructions**
To run the project:

1. Ensure all required datasets and intermediate files are in the home directory.
2. Unzip any `.zip` files into the home directory.
3. Execute the notebooks in the following order:
   - Start with `ML_final_project_data_filtering_&_matching.ipynb` to prepare the dataset.
   - Follow with `Data_Manual_Label_Finalized.ipynb` for manual labeling.
   - Run `Model_Choose_Cross_Validation_Finalized.ipynb` to select the best classification model.
   - Use `Data_Labeling_BERT_Finalized.ipynb` to label the entire dataset.
   - For clustering tasks, execute:
     - `Clustering_with_reviews.ipynb`
     - `Clustering_with_specs.ipynb`
     - `Clustering_w_matched_phones.ipynb`

---

### **Contact**
If any intermediate files are missing or issues arise, please contact us for assistance in obtaining the necessary files or resolving errors.
