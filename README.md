# ml-project-hub

**Topic: Sales Prediction**

**Overview:**
The project began with data cleaning, ensuring the datasets were well-prepared for analysis.
This involved dividing the data into training and testing sets, addressing missing values, and
standardizing categorical variables. The EDA phase included visualizing data through various
graphs to understand patterns, distributions, and relationships between different features.
Linear regression was employed to predict quantity based on the rating, and K-Means
clustering was applied to identify natural groupings within the data. Hyper parameter tuning
was also performed for the Random Forest Regressor to optimize its performance.

**Objectives:**
• Cleaning Data.
• Performing EDA.
• Linear Regression.
• Random Forest Regressor
• Gradient Boosting Regressor
• K-Means Algorithm.

**Before analysis of data we have performed data cleaning which include as
following:**
Firstly, we have divided our data set in two data sets with 70:30:

a Train Data
b Test Data

Clean and preprocess the data, addressing missing values
and inconsistencies.
Perform operations such as counting branches and product
lines, determining modes, and replacing categorical and
numeric values.
Cleaning Operations:
 Branch count.
 Product line count.
 Mode of Branch.
 Mode of Product line.
 Replacing the categorical and numeric columns of train and test data.
 Product line counts after replacement in train and test data.

**Performing EDA:**
We have done data visualization on different attributes which are shown below in different
form of graphs (bar graph, pie chart, and box plot) on both test and train data.
Visualize key attributes through various graphs (bar graphs, pie charts, and box plots) for both
Test and Train Data.
Explore relationships between variables, including product lines, gender distribution, customer
types, mean gross income, and payment methods.
(X-axis , Y-axis)
1. (Product line, No of Transactions).
2. (Gender, No of Transactions).
3. (Members, No Customer).
4. (Product Line, Mean Gross Income).
5. (Branch, Mean Gross Income).
6. (Percentage of payment methods (E -Wallet, Cash, Credit-Card)).
7. (Product Line, Female).
8. (Product Line, Male).
9. (Product Line, Ratios) (Composition of all branches).

   
**Linear Regression:**
 We utilize linear regression to predict the quantity based on rating in different
branches.
 Evaluate the model's performance using metrics such as mean absolute error, mean
squared error, linear regression score, and average linear regression score.
 And by using linear regression we are predicting the quantity on the basis of rating in the
branches.

**K-means Algorithm:**
 K-Means Clustering is an unsupervised learning algorithm that is used to solve the
clustering problems.
 Here we use the elbow method to find the K in K-means algorithm, and maintain our
clustering on given data set.

**Key Findings:**
**1. Linear Regression:**
The model exhibited good training and testing accuracies.
Mean absolute error, mean squared error, and R-squared score were used for
evaluation.

**2. K-Means Clustering:**
The elbow method was utilized to find the optimal number of clusters.
The K-Means algorithm was applied to cluster data based on certain attributes.

**3. Random Forest Regressor and Gradient Boosting Regressor:**
Both models were employed for prediction, and their performances were
evaluated.
Hyper parameter tuning was carried out to enhance the Random Forest
Regressor’s effectiveness.

**Conclusion:**
The project successfully achieved its objectives by cleaning and exploring the data, applying
linear regression for prediction, and utilizing the K-Means algorithm for clustering. The findings
provide insights into the relationships between different variables and offer predictive
capabilities for quantity changes in different branches. Further optimizations and fine-tuning
of models could enhance predictive accuracy in future iterations of the
