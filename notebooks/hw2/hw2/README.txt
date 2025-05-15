
Some Linear Classification Models
By: Amir Noori

Overview:
This homework uses different classification models being a perceptron, logistic regression, and linear SVC to test their accuracies with two different databases. The databases being a spam email checklist and a language model that differentiates english and dutch with added features.

Key Features:
First there is a perceptron implementation. 
Then a spambase dataset is loaded and split with the differing classification models tested against each other.
This process is repeated with the language model and once again with personally implemented data of sentences. 
This is done through training the data under the classification models and printing and tracking their results.

Files:
- `english.txt` / `dutch.txt`: Source text files
- `spambase.data`: Public UCI dataset for spam classification

To run this:
1. Open the Colab notebook.
2. Run each cell from top to bottom (or all at once using the Runtime --> Run All shortcut).
3. Ensure the files are uploaded properly and are in the same filepaths if running locally.
  - If there is an error there are commented lines in cell 1 that can be uncommented and run to upload the files and fix the issue.
4. View resulting model accuracy and confusion matrices for both tasks.

