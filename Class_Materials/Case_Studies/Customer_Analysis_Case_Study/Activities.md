# Activites List
<b>Important: for Activity 1, Activity 2 and  Activity 3 , please use the files [file1.csv](./Data/file1.csv), [file2.csv](./Data/file2.csv) and [file3.csv](./Data/file3.csv) from the [Data](./Data) folder.</b>
### Activity 1 (Monday)

- Aggregate data into one Data Frame using Pandas. Pay attention that files may have different names for the same column. therefore, make sure that you unify the columns names before concating them. 
- Standardizing header names
- Deleting and rearranging columns – delete the column customer as it is only a unique identifier for each row of data
- Working with data types – Check the data types of all the columns and fix the incorrect ones (for ex. customer lifetime value and number of open complaints ). Hint: remove the percentage from the customer lifetime value and truncate it to an integer value.
- clean the number of open complaints and extract the middle number which is changing between records. pay attention that the number of open complaints is a categorical feature.
- Filtering data and Correcting typos – Filter the data in state and gender column to standardize the texts in those columns
- Removing duplicates

### Activity 2 (Tuesday)
- Replacing null values – Replace missing values with means of the column (for numerical columns). Pay attention that the Income feature for instance has 0s which is equivalent to null values. (We assume here that there is no such income with 0 as it refers to missing values)
Hint: numpy.nan is considered of float64 data type.
- Bucketing the data - Write a function to replace column "State" to different zones. California as West Region, Oregon as North West, and Washington as East, and Arizona and Nevada as Central
- (Optional) Standardizing the data – Use string functions to standardize the text data (lower case)

<b>Important: for Activity 3 and Activity 4 , please use the [file Data_Marketing_Customer_Analysis_Round3.csv](./Data/Data_Marketing_Customer_Analysis_Round3.csv) from the [Data](./Data) folder.</b>

### Activity 3 (Wednesday)

- Get the numeric data into dataframe called `numerical` and categorical columns in a dataframe called `categoricals`.
(You can use np.number and np.object to select the numerical data types and categorical data types respectively)
- Now we will try to check the normality of the numerical variables visually
  - Use seaborn library to construct distribution plots for the numerical variables
  - Use Matplotlib to construct histograms
  - Do the distributions for different numerical variables look like a normal distribution 
- For the numerical variables, check the multicollinearity between the features. Please note that we will use the column `total_claim_amount` later as the target variable.
- Optional: Drop one of the two features that show a high correlation between them (greater than 0.9). If there is no pair of features that have a high correlation, then do not drop any features.

### Activity 4 (Thursday)

- Show a plot of the total number of responses.
- Show a plot of the response by the sales channel.
- Show a plot of the response by the total claim amount.
- Show a plot of the response by income.
- (Optional) Don't limit your creativity!  plot any interesting findings/insights that describe some interesting facts about your data set and its variables.
- Plot the Correlation Heatmap.
- Clean your notebook and make it a readible and presentable with a good documentation that summarizes the Data Cleaning, Exploration(including plots) Steps that you have performed.
