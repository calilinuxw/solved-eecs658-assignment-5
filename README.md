Download Link: https://assignmentchef.com/product/solved-eecs658-assignment-5
<br>
Deliverables:

<ol>

 <li>Copy of Rubric5.docx with your name and ID filled out (do not submit a PDF)</li>

 <li>Python source code.</li>

 <li>Screen print showing the successful execution of your Python code. (Copy and paste the output from the Python console screen to a Word document and PDF it).</li>

</ol>




Assignment:

<ul>

 <li>I have created an imbalanced iris dataset called “imbalanced iris.csv” to use for this assignment which is located in the Assignment 5 folder.</li>

 <li>Use 2-fold cross-validation with the Neural Network machine learning model for each part.</li>

 <li>This assignment has three parts (listed below by number). Before each part’s printout, printout the part number.</li>

</ul>

Part 1: Imbalanced Data Set

<ul>

 <li>Print out and label the Confusion Matrix and Accuracy score using the imbalanced iris data set.</li>

 <li>Print out and label the calculated Class Balanced Accuracy as described in the Imbalanced Datasets lecture.</li>

 <li>Print out and label the calculated Balanced Accuracy as described in the Imbalanced Datasets lecture.</li>

 <li>Print out and label the balanced accuracy score calculated by the scikit-learn function balanced_accuracy_score as described in the Imbalanced Datasets lecture.</li>

</ul>

Part 2: Oversampling

<ul>

 <li>Use the scikit-learn imblearn.over_sampling library (Imbalanced Datasets lecture) for each of the following:

  <ul>

   <li>Balance the imbalanced iris dataset with random oversampling and printout and label the Confusion Matrix and Accuracy score. (We don’t need to use one of the balanced accuracy scores from Part 1 because the set is balanced now).</li>

   <li>Balance the imbalanced iris dataset with SMOTE oversampling and printout and label the Confusion Matrix and Accuracy score.</li>

   <li>Balance the imbalanced iris dataset with ADASYN oversampling and print-out and label the Confusion Matrix and Accuracy score. Use the sampling_strategy=’minority’ parameter, or you will get an error message. (Note: the resulting dataset may still not be balanced, which is okay).</li>

  </ul></li>

</ul>

Part 3: Undersampling

<ul>

 <li>Use the scikit-learn imblearn.under_sampling library (Imbalanced Datasets lecture) for each of the following:

  <ul>

   <li>Balance the imbalanced iris dataset with random undersampling and printout and label the Confusion Matrix and Accuracy score.</li>

   <li>Balance the imbalanced iris dataset with Cluster undersampling and printout and label the Confusion Matrix and Accuracy score.</li>

   <li>Balance the imbalanced iris dataset with Tomek links undersampling and print-out and label the Confusion Matrix and Accuracy score. (Note: the resulting dataset may still not be balanced, which is okay).</li>

  </ul></li>

</ul>




Remember:

<ul>

 <li>Your Programming Assignments are individual-effort.</li>

 <li>You can brainstorm with other students and help them work through problems in their programs, but everyone should have their own unique assignment programs.</li>

</ul>