# python ETL template
A small python ETL example that you can use as a template or a starter point.

# dexription
THis template extracxt the data from CSV, JSON, and XML files then do some processing on it before loading it all into one CSV file (transformed_data.csv)
This template uses panda library as the main ETL library to process the data and export it in a CSV format.

# How to use
Edit the following methods as needed to do your ETL process you need
- Use extract_from_csv() to extract from CSV files
- Use extract_from_json() to extract from JSON files
- Use extract_from_xml() to extract from XML files
- Use transform() method for any processing on the data before saving it in the final file
- Add to log() method anything you require to log
