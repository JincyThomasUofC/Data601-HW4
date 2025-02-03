# Data601-HW4

Home Work 4
Data Analysis of Building Energy Benchmarking Data

 An in-depth analysis of the City of Calgary’s Building Energy Benchmarking dataset is performed in this assignment.  Python, Regular Expressions (Regex), Pandas (for minimal tabular operations), NumPy, Seaborn and Matplotlib are used to preprocess, analyze, and visualize the data. The tasks performed include cleaning the dataset, extracting relevant data using Regex, performing aggregations, detecting outliers, and conducting exploratory visualizations.

Regex expressions were used for extracting numeric values from text based columns  by matching all possible numeric patterns. Postal codes were cleaned and formatted to follow the Canadian format . The postal codes were removed from the address columns and regex expressions were used to match the formats. 

Five of the columns have more than 40 percent missing values . The energy value columns which had numerical data was text-based. Conversion had to be done. There were a significant amount of outliers which had to be replaced by the medians or modes of the corresponding columns. This can reduce the accuracy of the analysis. Since there were no dates, seasonal analysis was not possible.

Grouping and aggregation is used to extract meaningful insights and matplotlib and seaborn are used to visualize the patterns and findings.Statistical hypothesis  tests are also used.

Insights obtained: 
1.  office property types are the top energy consumers over 5 years from 2019 to 2023
2. Increasing demand for natural gas should be addressed appropriately. 
3. Reduced efficiency  over the years .It should be addressed properly by promoting more efficient energy resources.
4. Distribution sites are showing higher average EUI values over time making them least efficient property type
5.Over the analysis period from 2019 to 2023, health clubs and distribution centres are the dominant consumers of natural gas followed by ice curling rinks and offices.
   Proper resources should be allocated to these property types so that they can use more environment friendly and renewable energy sources.
6. GHG emissions are  directly related to the natural gas consumption. To reduce the GHG emissions, other alternative resources must be used.