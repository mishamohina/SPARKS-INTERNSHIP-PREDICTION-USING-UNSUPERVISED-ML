# SPARKS-INTERNSHIP-PREDICTION-USING-UNSUPERVISED-ML
From the given Dataset,predict the optimum number of clusters and represented it visually using Python Jupyter notebook.

The Iris Dataset considered as the Hello world of data science is used here.It contains five columns namely-Petal Length,Petal width,Sepal Length,Sepal width and Species type.
Iris is a flowering plant, the researchers have measured various features of different iris flowers and recorded them digitally.
The exploratory data analysis is used here to represent it visually.
EXPLORATORY DATA ANALYSIS
Exploratory Data Analysis(EDA) is a technique to analyze data using some visual techniques.With this technique, we can get detailed and the statistical information about the statistical summary and visual representation of the data.
The following steps were done to analyse and predict from the given dataset.

1.Downloading the dataset
The data is downloaded with .csv extension  from the given link.Then Pandas library is used to load this CSV file, and we will convert it into the dataframe .read_csv() method is used to read CSV files.

2.Getting Information about the data set
The shape parameter to get the shape of the dataset.It was analysed that dataframe contains 6 columns and 150 rows.
The columns and their data types was analysed using info() method.
A quick statistical summary of the dataset using describe() method.
This function applies statistical computations on the dataset like extreme values,count of data points standard deviation etc. 
Any missing value or NaN value is automatically skipped.describe() function gives a good picture of the distribution of data.


3.Checking Missing Values
It is crucial to check if data contains any missing values or not.
Missing values can occure when no information is provided for one or more items or for a whole unit.It is done for isnull() method.


4.Checking Duplicates
Having duplicates in data sets can disrupt the analysis.
Hence to check whether this data set contains any duplicates or not. 
Pandas drop_duplicates() method helps on removing duplicates from the data frame.
To see if the dataset is balanced or not i.e all the species contain equal amounts of vows or not. Series.value_counts() function.
This funcation returns a series containing counts of unique values.  


5.Data visulaization
The Matplotlib and Seaborn library is used for the data visualization.The following characteristics are observed from the charts.

 a)Relation between variables
   The relationship between sepal length and sepal width.
   The relationship between Petal length and petal width.
			
  b)Histograms
   Histograms shows the distribution of data for various columns.It can be used for uni as well as bi-variate analysis.
			
  c)Histograms with Histplot Plot
   Histplot is used basically for the univariant set of observations and visualizes it through a histogram i.e only one observation and hence we choose one particular column of the dataset.
			
  d)Box Plots
    The boxplots is use to see how the categorical value is distributed with other numerical values.
				

   
    
   

