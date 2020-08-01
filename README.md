
# Churn Modeling using ANN
* To use this dataset, use the following command:
  ```
  dataset = pd.read_csv('Churn_Modelling.csv')
  ```
* To run the notebook, you will need to install the following packages:
  ```
  pip install numpy
  pip install pandas
  pip install tensorflow
  pip install keras
  pip install matplotlib
  pip install sklearn
  ```

## Dataset Desciption
  * The dataset describes 14 numerical properties of people in different parts of Europe and is concerned with attributes that indicate if a particular customer is wanting to leave the bank. The dataset has the following input categories:
    * RowNumber
    * CustomerId
    * Surname
    * CreditScore
    * Geography
    * Gender
    * Age
    * Tenure
    * Balance
    * NumOfProducts
    * HasCrCard
    * IsActiveMember
    * EstimatedSalary
    * Exited
  * Input and output attributes are numerical & categorical and there are 10000 instances to work with.
  * Performance for models is evaluated using Confusion matrices for classification.
