## Web-Scraping project on Github topics page

### About Web-scraping
Web scraping is an automated method used to extract large amounts of data from websites quickly and efficiently. This process involves fetching web pages and extracting relevant information, which can then be stored and analyzed for various purposes such as data analysis, research, and machine learning.

### About Github (since we will scraping the topics page of github)
Well, since this is already on github, you know about it. Putting it simply, it's a disneyland for developers where projects come to life.

### About the project

This project aims to extract and analyze data from GitHub repositories for various topics using web scraping techniques. By scraping data from GitHub, we can gain insights into the most popular repositories, trends in different fields, and the activity levels of various projects.

#### Objectives
1. Scrape GitHub Repositories: Extract data from GitHub repository pages for specific topics.
2. Data Parsing and Storage: Parse the HTML content and store the extracted data in a structured format.

#### Technologies used
1. Python: All code is in python, since it is versatile
2. Jupyter-Notebook: It is the platform used to write the code

#### Libraries used
1. Pandas: For data manipulation
2. Requests: For sending HTTP requests
3. OS: To interact with the operating system, since we are saving the data in the form of csv's on the device
4. BeatifulSoup: Parsing HTML files and extract data

## Project workflow:
1. Setting up the environment
2. Web scraping
3. Data parsing and storage

All the code can be found in ['Web_scraping_github_repo.ipynb'](https://github.com/Omsaigadge/Web_scraping/blob/main/Web_scraping%20github_repo.ipynb), written purely in python.
The ['webpage.html'](https://github.com/Omsaigadge/Web_scraping/blob/main/webpage.html) , is the data which we get after a succesful connection, it will created automatically in the folder of the .ipynb file

The final results can be found in the zip file, ['topics_data.rar'](https://github.com/Omsaigadge/Web_scraping/blob/main/topics_data.rar), which has all the d=csv files created after scraping.
(An example of the data that is extracted is also present in the [3D.csv](https://github.com/Omsaigadge/Web_scraping/blob/main/3D.csv.csv)
