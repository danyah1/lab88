# lab88
The process started by importing the necessary libraries and loading the dataset. Exploratory data analysis was performed using a pairplot to visualize relationships between features colored by the target class.

The data was then split into training and testing sets. Since KNN relies on distance calculations, feature scaling was applied using StandardScaler to ensure all features contributed equally to the model.

A KNN classifier was created and trained on the scaled training data. The model achieved an accuracy of approximately 92.33% on the test set.

To improve performance, different K values from 1 to 40 were tested, and the error rate was plotted. The optimal K value was found to be 21, which yielded the lowest error rate compared to the default K=1.
