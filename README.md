# Lead-Scoring-Case-Study
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

<font color=blue> **Read Data**	<br>
* Import important libraries	<br>
* Read Leads data into dataframe	<br>
* Quick review of dataframe	<br>
* Shape of Leads dataframe¶	<br>
* Check for conversion rate in dataframe	<br>
	
**Analyze data and prepare data**	<br>
* Check for missing values	<br>
* Check level of categorical columns	<br>
* Identify columns that have default "Select" value	<br>
* Check for missing values	<br>
* Identify categorical columns with missing values	<br>
* Identify quantitative columns with missing values	<br>
* Calculate percentage missing values (Re-check)	<br>
* Checking distribution of these quantitative variables	<br>
* Impute quantitative columns	<br>
* Drop columns which has more than 70% missing values	<br>
* Impute missing values for categorical values with less missing values	<br>
* Update numcols and nonnumcols since we dropped few columns	<br>
* Boxplot for quantitative varibles	<br>
* Bivariate Analysis	<br>
* Outlier Analysis	<br>
* Create dummy variables	<br>
* Label encoding for other categorical columns	<br>
* Drop columns with no variance	<br>
* Checking correlation	<br>
	
**Data Preparation for Modeling**	<br>
* Train Test split	<br>
* Feature Scaling	<br>
	
**Model Building**	<br>
* Create a function for model building	<br>
* Feature Scaling	<br>
* Use RFE for feature selection	<br>
* Using statsmodel for rfe columns	<br>
* Predicting based on latest model	<br>
* Create confusion metrics	<br>
* Plot ROC Curve	<br>
* Find Optimal cutoff value	<br>
* Plot accuracy sensitivity and specificity	<br>
* Precision - Recall plot	<br>
	
**Making prediction on test set**	<br>
	
**Find Principal Components using PCA**	<br>
	
**Logictic Regression on PCA**	<br>
	
**Model Conclusion**	<br>
* Merging train and test prediction	<br>
* Merging predictions to original dataframe	<br>
* Creating Lead Score column	<br>
* Creating a dataframe with cutoff and conversion%	<br>
