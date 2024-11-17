# Tidyverse-Functions-with-Clinical-Data

https://87ba3b58ad3340dda13b6e3a231b86d4.app.posit.cloud/file_show?path=%2Fcloud%2Fproject%2FTidyverse-Functions-with-Clinical-Data.html   

Tidyverse for Clinical Data Analysis involves using a collection of R packages designed for data manipulation, cleaning, visualization, and reporting, which are essential in clinical trial workflows.     

Generate Sample Data: Created a dataset with 30 observations, including patient IDs, treatment group, age, weight, and blood pressure.         
    
Data Manipulation: Use dplyr functions:

filter() to subset data.

mutate() to create new columns (e.g., BMI).

group_by() and summarize() to compute group-level statistics

arrange() to sort data (e.g., by BMI).

Data Reshaping: Use tidyr functions:

pivot_longer() to reshape wide data into long format.

pivot_wider() to reshape long data back to wide format.

Data Visualization: Use ggplot2 to create plots like scatter plots and boxplots for visualizing relationships (e.g., age vs. BMI).

Functional Programming: Use purrr to apply functions across columns, like standardizing numeric variables.

File I/O: Use readr to read and write data in CSV format.    
