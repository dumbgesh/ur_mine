# K-Nearest Neighbors (KNN)

## KNN is an algorithm used for classification and regression.

Imagine a college wants to predict whether a student will pass or fail based on study hours. A new student studies 4 hours per day.

KNN looks at the K nearest students with known outcomes and uses their results to predict the new student's outcome.

For example, if \(K=3\), it checks the three most similar students. If two passed and one failed, KNN would classify the new student as Pass by majority vote.

### Logic Flow of KNN

1. Choose a value of \(K\), the number of neighbours.
2. Calculate the distance between the new data point and existing data points.
3. Find the \(K\) closest points.
4. Use majority voting to assign a class.