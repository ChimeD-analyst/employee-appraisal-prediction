# employee-appraisal-prediction
# HR Dataset
The steps carried out:\
Data Cleaning\
Data Exploration\
Model Development\
Model Interpretation/Evaluation
*	Data Cleaning\
This involved handling missing data and columns that had textual data ,such as  dates and employee names. Each employee has a unique identification number, so their names could be factored out without any consequences. Microsoft Excel was used to change the Performance Score column from textual categories to numerical categories. The Performance Score column contained the following features;
    * **Exceeds**: This means an employee exceeds the pass mark. This can be equated to an excellent performance.
    * **Fully Meets**: This means an employee fully meets the requirements. This isn’t an excellent performance but they passed.
    * **Needs Improvement**: This means an employee didn’t meet the requirements and needs improvement
    * **PIP**: This category had a very poor performance or we absent\

*	Data Exploration\
It helped understand the different variables by analyzing them through visualizations and statistics, the data set contains 36 columns in total and 25 columns were dropped after the data cleaning process. Feature scaling was carried out on the data to reduce the variance or difference in the range of values across the various columns, which brings all the various features between 0 and 1. Then the Principle Component Analysis was used on the scaled down data for dimensionality reduction to further improve performance.
*	Model Development\
After the data preparation and exploratory data analysis, I built the model on different algorithms such as the   decision tree , random forest and the artificial neural network. The data from the PCA was then passed into these classifiers to carry out training and testing.
*	Model Interpretation\
The model is to predict the appraisal of employees in a company. The employees were graded based on their perf twormance score. The model then predicts the various performance scores. Various evaluations were used such as accuracy, precision etc. 


