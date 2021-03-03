# Feature-engineering-part-1

## Handling Missing values:  
# What are different types of Missing Data?
  There are 3 types of missing values 
  
   1. Missing completly at random (MCAR):
      Missing completely at random (MCAR) is the only missing data mechanism that can actually be verified. Missing data are MCAR when the probability of missing data on a               variable is unrelated to any other measured variable and is unrelated to the variable with missing values itself.

   2. Missing data not at Random (MNAR):(Systematic missing value)
      There is absolute some relationship between the data missing and any other values, observed or missing, within the dataset. example : Age and cabin
      
    3.Missing At Random(MAR): 
     When the people delibrately hide or not want to answer a specific question. for example :-      Men--- hide their salary, Women --- hide their age
  
 ## So we are going to use some techniques to handle missing values 
   1.  Mean/ median imputation. 
        When we should apply?
          Mean/Median imputation has assumption that the data are completely at random(MCAR).We solve this by replacing the NAN with
          most frequent occurence of the vairiable.For more info. check my ".ipynb file"



