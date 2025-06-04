# Eniac_DiscountAnalysis
Eniac is an E-Commerce platform specialized in tech products. They tried for a while to increase their business by increasing discounts. The task at hand is to analyze the effectiveness of those disocunts to enable decision making regarding their future sales strategy. The database containing transactions requires major cleaning efforts in advcance. 

## Getting Started
The raw data is located in `csv` format in the `data_raw` folder. Example data transformations using Panda can be found in the IPython Notebook `01_datacleaning.ipynb`. As a next step, `02_categorization.ipynb` contains categorization using methods of analyzing the product description entries. To skip the transformation process, the clean database can be accessed in the `data_clean` folder using `csv` files. The data aggregation and vizualization steps can be found within the `03_dataviz.ipynb`. This notebook contains product category specific timeseries analysis on a monthly basis to compare and evaluate the effectiveness of Eniac's discounts. 

## Data Insights
The evaluated sales within the dataset show a strong seasonality. Upticks in sales can be found during November and December for Black Friday and Christmas. Start of year sales are slow across all categories. Specific to product categories the following images highlight upticks in discounts that are either matched by a month-to-month increase in revenue or fail to increase customer spending hinting at a failed effort to draw in more custommers and generate a higher volume of sales to offset decreased sales margins. 
