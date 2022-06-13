# JavaVsPythonMLlibs
## A Comparison of Java Tribuo and Python scikit-learn Machine Learning Libraries

This project contains a set of Jupyter notebooks and the datasets they use, which are the basis of the work for a research project. 

This is the abstract for the reseach paper:

This paper makes a rigorous comparison between the scikit-learn library for Python and the Tribuo library for Java. The machine learning tasks of classification, regression, and clustering are performed using both libraries while keeping each task's dataset fixed. The same algorithms which are implemented in both libraries are compared. Furthermore, each library's best scoring algorithm is identified for a given machine learning task, out of all the algorithms implemented in that library. To compare the results of the classification experiments the F1 score is used because the dataset is unbalanced. Results of the regression experiments are compared using the RMSE and R-squared scores, and clustering is compared using adjusted mutual information values. The training times for all experiments are noted. The results from these experiments show that Tribuo and scikit-learn are very evenly matched in their capabilities as machine learning libraries. Considering other factors, such as documentation and supporting libraries, if given the choice between scikit-learn and Tribuo for a new machine learning task, scikit-learn is the best choice. Since there are numerous Java enterprise applications running in production today, identifying Tribuo as a robust and performant machine learning library that can be used natively in a Java project is a valuable conclusion.
 
Note: The version of scikit-learn being used is 0.24.1 with Python 3.9.1. The version of Tribuo is 4.1 with Java 12.0.2.
