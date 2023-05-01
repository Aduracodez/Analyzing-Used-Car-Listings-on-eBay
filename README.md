# Analyzing Used Car Listings on eBay

This is a project that analyzes used car listings on eBay to gain insights into the used car market. The data used in this project was scraped from eBay using Python's requests and beautifulsoup libraries.

## Data Collection

The data-collection folder contains the Python script data_collection.py that was used to scrape the used car listings from eBay. The script scrapes information such as the car make, model, year, mileage, and price, among other attributes, and saves it in a CSV file.

To run the script, you will need to have Python 3.x and the requests and beautifulsoup libraries installed. You can install these libraries using the following command:

## Copy code

pip install requests beautifulsoup4

After installing the libraries, navigate to the data-collection folder and run the data_collection.py script using the following command:

Copy code

python data_collection.py

The script will take some time to run, depending on the number of listings you are scraping.

## Data Cleaning and Analysis

The data-analysis folder contains the Python notebook data_analysis.ipynb that was used to clean and analyze the data collected from eBay.

To run the notebook, you will need to have Python 3.x and the following libraries installed: pandas, numpy, matplotlib, and seaborn. You can install these libraries using the following command:

## Copy code

pip install pandas numpy matplotlib seaborn

After installing the libraries, navigate to the data-analysis folder and run the jupyter notebook command to start the Jupyter notebook server. Then, open the data_analysis.ipynb notebook and run each cell to execute the code and view the analysis.

The notebook contains a step-by-step analysis of the used car listings, including data cleaning, exploration, and visualization. The analysis includes:

Distribution of car prices

Distribution of car mileage

Correlation between car age, mileage, and price

Top 10 most popular car models on eBay

## Conclusion

This project provides insights into the used car market on eBay. The analysis shows that the most popular car models on eBay are Japanese and German brands, and that car prices and mileage are positively correlated. The data can be used by individuals or businesses interested in buying or selling used cars on eBay.
