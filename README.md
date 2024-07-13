Gitex Morocco Data Analysis Project
Overview
This project involves scraping data from the Gitex Morocco website, preprocessing the data, and visualizing it using Power BI. The dashboard created provides insights into the number of companies participating in Gitex Morocco and their geographical distribution.

Table of Contents
Introduction
Data Collection
Data Preprocessing
Data Visualization
Usage
Results
Future Work
Contributing
License
Introduction
Gitex Morocco is a significant technology event featuring numerous companies from around the world. This project aims to analyze the data of these companies to provide insights into their distribution and other relevant metrics.

Data Collection
Tools Used
Web Scraping: Python (BeautifulSoup, Requests)
Process
Data was scraped from the Gitex Morocco website. The information collected includes company names, locations, and other relevant details.

Data Preprocessing
Tools Used
Python Libraries: pandas, numpy
Steps
Cleaning: Removed duplicates, handled missing values, and standardized data formats.
Transformation: Converted textual data into a suitable format for analysis.
Exporting: Cleaned data was exported to a CSV file for further use.
Data Visualization
Tool Used
Power BI
Dashboard Features
Company Count: Total number of companies.
Geographical Distribution: Interactive map showing where companies are from.
Sector Analysis: Breakdown of companies by industry sector.
Usage
Requirements
Python 3.x
BeautifulSoup
selenuim
Requests
pandas
numpy
Power BI
Instructions
Clone the repository:

Copy code
git clone https://github.com/hamzahrd/gitex-morocco-analysis.git
Navigate to the project directory:

cd gitex-morocco-analysis
Install the necessary Python packages:

pip install -r requirements.txt
Run the web scraping script to collect the data:

python final-giex1.ipynb
Process the data:

python preprocessing.ipynb
Open the Power BI dashboard file (Gitex Rapport.pbix) to view the visualizations.
Results
The Power BI dashboard provides a comprehensive overview of the companies participating in Gitex Morocco. Key insights include the total number of companies, their geographical distribution, and a sector-wise breakdown.

Future Work
Enhanced Analysis: Incorporate additional metrics and KPIs.
Automation: Automate data scraping and dashboard updates.
Predictive Analytics: Use machine learning to predict trends and patterns.
Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

License
This project is licensed under the MIT License - see the LICENSE file for details.

