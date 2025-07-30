Libraries Used

The following Python libraries were used in this project:

- NumPy  
- Pandas  
- Matplotlib  

## 🧹 Data Cleaning

The dataset contained several missing and incorrect values. The first step was to identify and correct inaccurate data entries or convert them into missing values.

For example, in the Country column, some country names were misspelled. These were corrected using appropriate string replacement methods.

Next, we analyzed the relationships between features to determine suitable strategies for filling in missing values. We used:

- fillna() method to replace missing values
- If fillna was not sufficient, we used the mode (most frequent value) for imputation. This method was particularly applied to the Customer ID column.

For the records that could not be filled meaningfully, we chose to remove them.

## 📊 Data Analysis

At the end of the process, we identified the four countries with the lowest sales. Among them, we extracted the 10 individual records with the lowest sales.

We then calculated the average sales of these low-performing records and compared them to the overall sales average using a visual chart to provide insight into performance distribution.
