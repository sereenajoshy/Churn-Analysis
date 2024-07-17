# Customer Churn
"Churn Rate" is a business term describing the rate at which customers leave or cease paying for a product or service.Consequently, there's growing interest among companies to develop better churn-detection techniques, leading many to look to data mining and machine learning for new and creative approaches. This is a post about modeling customer churn using Python.
# DataSet
The data set I'll be using is a longstanding telecom customer data set.

The data is straightforward. Each row represents a subscribing telephone customer. Each column contains customer attributes such as phone number, call minutes used during different times of day, charges incurred for services, lifetime account duration, and whether or not the customer is still a customer.
# Environment
- Jupyter Notebook is used to code/develop the project.
- Python’s popular ML library Scikit-learn is used to build the model.
- For preprocessing LabelEncoder is used.It converts categorical labels (strings or numbers) into a format that can be provided to machine learning algorithms which means 0s and 1s.
- 'drop' method is used for data cleaning process. It is a specific method provided by pandas DataFrames. It is used to remove columns or rows from a DataFrame based on specified labels.
- Then data visualisation,two methods are used:
  * Scatter Plot: Used to visualize the relationship between two variables (here, 'VMail Plan' and 'Churn?')
  * Histogram Plot: Used to visualize the distribution of a single variable (here, 'VMail Message')
- The train_test_split function is used to split the dataset into two subsets,x and y for training and testing purposes.
- Finally classification and prediction process,
  * KNeighborsClassifier: It is an instance-based classifier that predicts the class of a data point by identifying its nearest neighbors in the feature space, making it effective for smaller datasets and 
    straightforward classification tasks.
  * SVC (Support Vector Classifier): It constructs hyperplanes in high-dimensional space to separate classes, using various kernels like linear, polynomial, or radial basis function(here, linear) to handle 
    complex decision boundaries and is suited for larger datasets and tasks requiring non-linear classification or regression.

                   

  

