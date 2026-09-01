Customer Attrition Data Analysis
1. Project Overview

This project uses Python and Pandas to explore a customer dataset containing 10,127 records and 23 columns. The dataset contains information about customer demographics, account information, credit information, and transaction activity. The main goal of the project was to organize the data, explore customer characteristics, and investigate patterns associated with customer attrition.

The project provided an opportunity to practice working with DataFrames, examining different data types, grouping records, calculating statistics, and creating visualizations to communicate findings.

2. Dataset and Tools

The primary tool used for this project was Python with the Pandas library. The dataset includes variables such as customer age, gender, education level, income category, card category, credit limit, total revolving balance, transaction amount, and transaction count.

The DataFrame.info() output showed that the dataset contains 10,127 entries and 23 columns. The columns include integer, floating-point, and object/string data types.

3. Analysis Process

I began by loading the dataset into a Pandas DataFrame and examining its structure. I used methods such as info(), value counts, grouping, and summary statistics to understand the available variables.

I then compared customer characteristics based on the attrition field. This allowed me to investigate whether variables such as transaction activity, credit information, and customer demographics differed between customers who remained with the company and customers who left.

I also created visualizations to make the results easier to interpret.

4. Results and Findings

One of the main goals of the analysis was to identify patterns that could help explain customer attrition. I compared different customer attributes and transaction behaviors between the two attrition groups.

The visualizations helped make differences in the data easier to see than looking only at raw DataFrame output. The analysis also demonstrated how Pandas can be used to transform a large dataset into smaller summaries that are easier to interpret.

5. Challenges and Debugging

One challenge was understanding the large number of columns in the original dataset. The initial DataFrame information output was lengthy and difficult to interpret because there were many variables.

I addressed this by examining individual columns and grouping related variables together during the analysis. Another challenge was deciding which variables would provide the most useful comparisons for understanding customer behavior.

6. What I Learned

This project improved my experience working with Python DataFrames and real-world-style datasets. I practiced inspecting data, grouping records, calculating statistics, and creating visualizations.

I also learned that data analysis involves more than simply loading a dataset. Choosing meaningful variables, checking the structure of the data, and presenting results clearly are important parts of communicating an analysis.

