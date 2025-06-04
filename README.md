# Eniac_DiscountAnalysis
Eniac is an E-Commerce platform specialized in luxury tech products, mainly from Apple. They tried for a while to increase their business by increasing discounts. The task at hand is to analyze the effectiveness of those disocunts to enable decision making regarding their future sales strategy. The database containing transactions requires major cleaning efforts in advcance. 

## Getting Started
The raw data is located in `csv` format in the `data_raw` folder. Example data transformations using Panda can be found in the IPython Notebook `01_datacleaning.ipynb`. As a next step, `02_categorization.ipynb` contains categorization using methods of analyzing the product description entries. To skip the transformation process, the clean database can be accessed in the `data_clean` folder using `csv` files. The data aggregation and vizualization steps can be found within the `03_dataviz.ipynb`. This notebook contains product category specific timeseries analysis on a monthly basis to compare and evaluate the effectiveness of Eniac's discounts. 

## Data Insights
The evaluated sales within the dataset show a strong seasonality. Upticks in sales can be found during November and December for Black Friday and Christmas. Start of year sales are slow across all categories. Specific to product categories the following images highlight upticks in discounts that are either matched by a month-to-month increase in revenue or fail to increase customer spending hinting at a failed effort to draw in more custommers and generate a higher volume of sales to offset decreased sales margins. The following graph for the product category "Cases and Protectors" serves as an example to showcase some of the observed connections between Discounts and Customer behavior.
![ts_qty_cases](https://github.com/user-attachments/assets/baea1dc2-3c7c-43be-a745-1d3999060b9d) <br>
In `July 2017` an increase in Discounts over all of the observed percentile bands corresponds to more than doubled amount of sold items within the category, showcasing a desired interaction between discounts and successful customer acquisition. On the flip side during `February 2018`, despite carrying over a high level of discounts from January, the success of the start of year sales could not be replicated and sales numbers dipped by more than 50%. The decrease calls into question whether the low sales would have been even worse with lower discounts of if lower discounts would have resulted in larger margins per sold item. For the black shopping month and holiday season in `November 2017` and `December 2017` despite chooosing a more defensive discount strategy compared to October, the platform had 2 of its top 3 months in terms of sales. While this does not explain necessarily that the strategy is the best long term it highlights its position in a busy market even when not offering the highest discounts.
Next to time series vizualizations, the `03_dataviz.ipynb` allows the user to also generate boxplots and bar charts for further analysis of the activities on the Eniac platform.

## Utilized Toolkit
- Python
- Pandas
- Matplotlib
- Seaborn
