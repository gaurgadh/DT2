## Video Game Sales Analysis

*Overview*

This repository contains Python scripts for analyzing video game sales data obtained from a provided dataset. The scripts primarily focus on calculating and comparing average global sales before and after the year 2005, and labeling records accordingly.

*Getting Started*

### Prerequisites

Make sure you have the following installed:

- Python
- Pandas
- pymysql
- sqlalchemy

### Installation

1. Clone this repository to your local machine.
2. If you’re using analyze_sales.py, modify the database connection string to connect to your MySQL database.
3. If you’re using analyze_sales_csv.py, ensure that the CSV file named vgsales.csv is available in the same directory as the script.

*Running the Tests*

Execute either of the Python scripts (analyze_sales.py or analyze_sales_csv.py). Both scripts will output the average global sales before and after 2005, along with a statement indicating which period had higher average sales.

*Breakdown of Tests*

- Connect to the database (if using analyze_sales.py).
- Load data from CSV (if using analyze_sales_csv.py).
- Calculate average sales before and after 2005.
- Label records as ‘pre-2005’ or ‘post-2005’.

*Deployment*

If applicable, provide instructions on deploying your project to a production environment.

*Author*

This analysis was conducted by Gaurav and Diksha.

*License*

The project is released under the MIT license.

*Acknowledgment*

We extend our gratitude to Professor Omar Al Trad for providing the dataset used in this analysis for educational purposes in the course “Data Analytics Tools.”
