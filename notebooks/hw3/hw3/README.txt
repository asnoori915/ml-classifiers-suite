
Naive Bayes and Decision Trees
By: Amir Noori

Overview:
This homework uses two classification models being Naive Bayes and Decision Trees to test their accuracies with two different datasets. The datasets being a mushroom dataset to classify edibility and a congressional voting record dataset to classify political party.

Key Features:
First, the Naive Bayes classifier is implemented using Laplace smoothing.
Then the mushroom and vote datasets are loaded and split with the Naive Bayes model tested on both.
The same process is repeated using a Decision Tree classifier built from scratch using entropy and information gain.
Each custom model is then compared to their sklearn equivalents to see how they match up.
This is done by training the data under the classification models and printing and tracking their results.

Files:
- `mushroom.csv`: Mushroom classification dataset (UCI)
- `votes.csv`: Voting records dataset (UCI)

To run this:
1. Open the Colab notebook.
2. Run each cell from top to bottom (or all at once using the Runtime --> Run All shortcut).
3. All files are automatically downloaded and preprocessed during execution.
4. View resulting model accuracy and confusion matrices for both tasks.

