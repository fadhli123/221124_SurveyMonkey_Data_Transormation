# 221124_SurveyMonkey_Data_Transormation

In this project I'll transform data layout as desired by client using excel and python.

## Raw Data

In the picture below is raw data given by client in. There are many 'Response' Columns for every Questions Column. Client wants to make Respons Column to be SubQuestions Column and trace every answer for each SubQuestion.  
![image](https://user-images.githubusercontent.com/110689945/205905893-29761a46-b282-4258-8f48-2ec2c535764a.png)

The desired format as below :
![image](https://user-images.githubusercontent.com/110689945/205906990-02bcfe90-770d-4a5c-bdf5-794d04a5cb26.png)
As we can see client also want to add new column representing total respondent for each Question and counting total same answer for each SubQuestion.

## Edit Data in Excel

In order to achive the final output, I edited the data layout first in excel as below:
![image](https://user-images.githubusercontent.com/110689945/205908510-bdeb41cc-7699-49c7-a383-cc3f353999c5.png)
Then pivoting table to make it column headers so we dividing every SubQuestion column: 
![image](https://user-images.githubusercontent.com/110689945/205909058-cddda543-6a26-4142-81f5-c8c15ab70f2d.png)

## Edit Data in Python

Then I edit the data using python in jupyter notebook. Start by make the dataframe, cleaning the data, modifying, adding new column, join column, then finally exporting the dataframe into excel format.
For the detail you can check this jupyter notebook file in my repository (221124_Data_Transformation .ipynb)

## Final Output
![image](https://user-images.githubusercontent.com/110689945/205910117-b60a3262-11a3-4554-b623-e45610088b98.png)
