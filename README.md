# 🌬️ The Weather Today In Paris 🌡️

## Project Overview
Welcome to "The Weather Today In Paris" GitHub repository! This project provides a comprehensive look at the current weather in Paris by utilizing the OpenWeather API and storing the data in MongoDB. The primary goal is to retrieve, process, and visualize weather information in a user-friendly manner.

## Libraries
The project leverages various Python libraries, including `requests`, `json`, `pymongo`, `pandas`, `numpy`, `ast`, `matplotlib`, and `seaborn`, to facilitate data retrieval, manipulation, and visualization.

## OpenWeather API Connection
To access real-time weather data, an OpenWeather API key is required. The project ensures a seamless connection by retrieving the key from a configuration file. Users are prompted if the key is missing, ensuring a smooth setup process.

## MongoDB Integration
Weather data is stored in MongoDB using the `pymongo` library. The MongoDB Compass connection is established to retrieve and visualize stored data easily.

## Data Retrieval and Storage
The project fetches weather information for Paris from the OpenWeather API, appends a timestamp, and stores the data as a document in the MongoDB collection named "openweather."

## Data Cleaning and Normalization
The retrieved JSON data is normalized into a pandas DataFrame for easy analysis. The project focuses on cleaning and structuring the data for better readability and understanding. Date and temperature values are converted to appropriate formats.

## Data Visualization
The final step involves visualizing key weather parameters such as temperature, feels-like temperature, minimum temperature, and maximum temperature. A bar chart is created using Seaborn and Matplotlib to present a clear overview of the day's weather in Paris.

Feel free to explore the code and documentation to understand the project's workflow better. Your feedback and contributions are highly valued! 🚀

**Notebook:** [The Weather Today In Paris]()

**MongoDB Compass Screenshot:** [MongoDB Compass Visualization]()
