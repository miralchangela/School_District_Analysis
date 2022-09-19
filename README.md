# School District Analysis
Click on the link to view the school district analysis: [School District Analysis](https://github.com/miralchangela/School_District_Analysis/blob/main/PyCitySchool_Challenge.ipynb)
# Overview of school district analysis
School district analysis  is for analysing  information  from a variety of sources and in a variety of formats.Main task is  preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. This analysis is used to inform discussions and strategic decisions at the school and district level.
## Collect the data 
In this phase , we collect the data for analysis by importing it into a structure that Python and Pandas can work on.the data is in .CSV format. Import the data from .CSV file into a dataframe named student_df by using pandas read_csv function and the OS module.data head part shown below:

![collect data](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/Collect_data.png)

## Prepare the data
In this phase, we clean the data to account for missing, incomplete, erroneous and duplicated data. This phase also includes manipulating segments of the dataset to highlight the relationships among variables.
- *Missing data:*
- pandas represents missing values by using  a data type that known as a Nan.using this function, we can identify the missing values and either remove or drop them.Another way to handle missing value is filling or replacing them by zero or mean of perticular row. In the precending image shows number of missing values and droping missing values.

![misssing values](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/missing_data.png)

- Below image shows the result of dropped missing values.

![missing values solution](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/missing_data_solution.png)

- *Erroneous data:*
- Datasets have additional types of dirty data. These include typos, misplaced data, mixed data types, and incorrect symbols or punctuation. You need to fix all these problems when preparing data for an analysis.Image gives the result of after handling the dirty data.

![Dirty data](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/dirty_data.png)

- Below image shows the result of dropped dirty data.

![Dirty data solution](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/dirty_data_solution.png)

- *Duplicates Data:*
- Pandas offers the duplicated function for identifying duplicated rows in a DataFrame.we can also drop duplicates when we are preparing for analysis. In the precedding image shows number of duplicates and result after dropped duplicates.

## Summarize the data
- We can summarize the data present in the data frame using describe() method. This method is used to get min, max, sum, count values from the data frame along with data types of that particular column.The following image shows result of describe method.

![Summarize data](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/summarize_data.png)

## Drill Dwon into the data
In Pandas, we can do a targeted analysis by using location functions. With these functions, we can select or update areas of interest in a DataFrame. The two location functions that are the most commonly used are *loc* and *iloc*. Using this function we can also summarize single column. *loc* is used to select row by index where *iloc* used to select rows bu integer based location.

## Compare the data 
To compare the data aggregations, or groups, that we created by using the groupby function, we need to use a Pandas aggregation function. The aggregation functions are functions that each return a single value when applied to an entire column.

![Compared data](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/Compared_data.png)

- In the preceding image , we can find the average budget for each school type by using the groupby and mean functions.
- In the below image , we can find the total numbet of student at each school and sort this number to largest to smallest(descending  order).

![total number student](https://github.com/miralchangela/School_District_Analysis/blob/main/Resources/student_count_data.png)

## Analyze the data
This phase consists of an iterative process and varies depending on the goal of the analysis or research. Regardless of the specifics, the analysis involves testing a thesis, reviewing the results, and refining both until we reach a conclusion.
- From the analysis , we can see that public school budget is more than Charter school.
- Average of math score is lower than reading score for all combined students in grades 11 and 12.
- This analysis also gives information about total number of students in each school.
- we can also find the average math  and reading score by grade for each school type.










