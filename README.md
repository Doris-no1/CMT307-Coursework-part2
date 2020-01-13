# CMT307-Coursework-part2
The open-source project of my implementation on part2 of CMT307 coursework, the problem to be solved is a sentiment analysis on IMDb dataset

# How to run the code
The code is organized in 'WorkOnIMDb.ipynb' with Jupyter Notebook.
The code is expected to run with Google Colab environment. 
The data folder need to be placed in the 'Colab Notebooks/AML-Coursework' directory and thus the code can run directly.

# Processing Instructions
Code comments have been added within the provided Jupyter Notebook. Please check the notations to figure out the code logic.

The processing stages include:
0. Import dependencies
1. Load data
2. Preprocessing and deriving the frequency-based feature (TF-IDF)
3. Extration of the 2nd feature N-gram (N=2)
4. Extraction of the 3rd feature - Word2Vec
5. Feature selection
6. Feature combination and further selection
7. Train the classification model and evaluation on the development set
8. Modify the feature selection scheme and re-test on the development set
9. Evaluation on the test set and report the final results

# Performance Measurements
The whole process achieves classification precision of 83.6%, recall of 83.5%, f1 score of 83.5%, and accuracy of 83.5% on the IMDb dataset.
