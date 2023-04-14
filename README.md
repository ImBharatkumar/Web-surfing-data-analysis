# Web-surfing-data-analysis
This repository contains code and data to analyze web surfing data. The data contains information about web surfing such as country, domain, device, screen width, screen height, domain category, installation day, pageviews, and device type. The aim of this analysis is to gain insights into the behavior of web surfers and to understand their preferences.

# Data
The data is stored in a CSV file called web usage.csv. It contains the following columns:

Country: The country where the web surfer is located.
Domain: The domain of the website the web surfer is visiting.
Device: The type of device the web surfer is using (e.g. desktop, mobile, tablet).
Screen_width: The width of the screen the web surfer is using in pixels.
Screen_height: The height of the screen the web surfer is using in pixels.
DomainCategory: The category of the website the web surfer is visiting (e.g. news, sports, entertainment).
Installation_day: The day when the web surfer installed the browser or app used to surf the web.
Pageviews: The number of pages the web surfer has visited.
device_type: The type of the device used to surf the web (e.g. iOS, Android, Windows).

# Analysis
The analysis of the web surfing data is done using Python 3. The main script is called web_surfing_analysis.py. It reads the data from the web_surfing_data.csv file, cleans it, and performs various analyses. The results of the analysis are printed to the console and saved in various files, such as country_analysis.txt, domain_analysis.txt, and device_analysis.txt.

# Dependencies
The following Python libraries are required to run the analysis:

pandas
numpy
matplotlib
seaborn

# Running the Analysis
To run the analysis, follow these steps:

Clone this repository to your local machine.
Install the required dependencies.
Run the web_surfing_data_analysis.ipynb script using jupyter notebook.
