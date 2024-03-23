# FAAMechanicalDataScraper

## This script was created for educational purposes under the assumption of permissibility for non-commercial, nonprofit use. 

FAAMechanicalDataScraper is a Python-based tool designed for aviation data enhancement. It automates the extraction of mechanical data from the FAA registry, addressing the need for comprehensive aircraft reliability analysis. Key features include scraping with Selenium, BeautifulSoup (HTML parsing), and pandas for data manipulation/integration.


The FAAMechanicalDataScraper is a specialized tool developed to enrich aviation datasets with detailed mechanical data. This script navigates FAA.gov to extract publication dates and other critical data related to planes, handling various date formats and merging this data into an existing dataset.

It is designed to enrich aviation data by extracting detailed information about aircraft from the FAA registry. This script navigates to FAA's official aircraft inquiry page, inputs tail numbers from an input CSV file, and scrapes aircraft details such as manufacturer, model, type, engine type, and certification dates. It carefully manages request rates to respect FAA's website and updates the dataset with newly fetched data.
