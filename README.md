## 🌸 KNN Classifier with the Iris Dataset

This is a simple machine learning project where I used the K-Nearest Neighbors (KNN) algorithm to classify flowers from the famous Iris dataset. The goal is to see how well KNN can predict the species of an iris flower based on its petal and sepal measurements.


## 📁 About the Dataset

The Iris dataset contains 150 samples of iris flowers from 3 different species:
Iris-setosa, Iris-versicolor, and Iris-virginica.

Each sample includes 4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width


The target column is Species.

## 🔧 What I Did
1. Loaded the dataset from a CSV file


2. Normalized the feature values using StandardScaler


3. Encoded the Species column (from strings to numbers) using LabelEncoder


4. Split the data into training and testing sets


5. Trained a KNN model with different values of K (1, 3, 5, 7)


6. Checked the accuracy and created confusion matrices


7. Plotted the decision boundaries to visualize how the classifier works

  ## 📈 Example Output (K=3)
  ![knn_decision_boundaries](https://github.com/user-attachments/assets/4fa328bb-3ec2-4303-be95-419b5d2f8bee)

##  ✅ Results

The model performed really well, even achieving 100% accuracy for some values of K.

The decision boundary plot clearly shows how KNN separates the classes based on feature values.


##🧠 Key Learnings

Normalization is super important in KNN since it uses distances.

Choosing the right K is crucial — smaller values can overfit, and larger ones may underfit.

Visualizing the boundaries gives great insight into how the model makes decisions.

## 🛠️ Requirements

You'll need:

Python 3.9

pandas

numpy

matplotlib

scikit-learn

## 🚀 How to Run
1. Clone this repo or open the notebook in Google Colab


2. Upload your iris.csv file if needed


3. Run the notebook cell by cell to see how everything works!

 ## 📌 License

This project is open-source and free to use under the MIT License.  


