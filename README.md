# 🌬️ The Weather Today In Paris 🌡️

## Project Overview
Welcome to "The Weather Today In Paris" GitHub repository! This project provides a comprehensive look at the current weather in Paris by utilizing the OpenWeather API and storing the data in MongoDB. The primary goal is to retrieve, process, and visualize weather information in a user-friendly manner.

## Libraries
The project leverages various Python libraries, including `requests`, `json`, `pymongo`, `pandas`, `numpy`, `ast`, `matplotlib`, and `seaborn`, to facilitate data retrieval, manipulation, and visualization.

## OpenWeather API Connection
To access real-time weather data, an OpenWeather API key is required. The project ensures a seamless connection by retrieving the key from a configuration file. Users are prompted if the key is missing, ensuring a smooth setup process.

###### When we cannot use an API key to collect data, we explore other ways to gather the information we need. One such method is web scraping, which involves extracting data from websites., you can find additional details in the [Web Scraping using BeautifulSoup or Seleniums Project](https://github.com/CatelloTheDataProjectManager/Web_Scrapping/blob/main/README.md)).

## NoSQL database solutions

Database solutions that offer alternative approaches to data storage and management compared to traditional relational databases. The choice between MongoDB and HBase depends on the specific requirements of the application and the type of data being stored.

- ***MongoDB*** is particularly well-suited for storing semi-structured data, where the schema can vary from document to document. Semi-structured data can take many forms, such as JSON documents, XML documents, or CSV files with varying numbers of columns.
- Instead Sparse data is often stored in ***HBase***, where each row can have many columns, but only a small fraction of the columns may have values. HBase is optimized for sparse data, because it stores only the non-empty cells, which can result in significant space savings compared to traditional relational databases.

###### (If you are interested in exploring a project that uses HBase database, you can check out the following link: [HBase Database Project](https://github.com/CatelloTheDataProjectManager/HBaseDatabase/blob/main/README.md)

## MongoDB Integration
Weather data is stored in MongoDB using the `pymongo` library. The MongoDB Compass connection is established to retrieve and visualize stored data easily.

## Data Retrieval and Storage
The project fetches weather information for Paris from the OpenWeather API, appends a timestamp, and stores the data as a document in the MongoDB collection named "openweather."

<img src="https://github.com/CatelloTheDataProjectManager/The-Weather-Today-In-Paris/blob/main/PyMongoData.png" width="600">

## Data Cleaning and Normalization
The retrieved JSON data is normalized into a pandas DataFrame for easy analysis. The project focuses on cleaning and structuring the data for better readability and understanding. Date and temperature values are converted to appropriate formats.

###### (In this notebook, we explore techniques for handling nested JSON structures.But for a deeper dive into this topic, you can find additional details in the [Earthquake-Coordinates Project](https://github.com/CatelloTheDataProjectManager/Earthquake-Coordinates/blob/main/README.md)).



## Data Visualization
The final step involves visualizing key weather parameters such as temperature, feels-like temperature, minimum temperature, and maximum temperature. A bar chart is created using Seaborn and Matplotlib to present a clear overview of the day's weather in Paris.

**Jupyter Notebook:** [The Weather Today In Paris](https://github.com/CatelloTheDataProjectManager/The-Weather-Today-In-Paris/blob/main/The%20Weather%20Today%20In%20Paris.ipynb)

Feel free to explore the code and documentation to understand the project's workflow better. Your feedback and contributions are highly valued! 🚀

<img src="https://github.com/CatelloTheDataProjectManager/The-Weather-Today-In-Paris/blob/main/weather_temperatures_in_paris.png" width="600">





