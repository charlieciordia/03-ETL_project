# 03-ETL_project

Data mining mood⬇️

![kermit](https://github.com/charlieciordia/03-ETL_project/blob/main/img/kermit2.gif)

## Goal 🎯

The purpose of this project is to extract, transform and load data from multiple sources.

The objective in this project is to collect data on air quality in different Spanish cities, as well as on passenger journeys according to different transport modes. Subsequently, after collecting more relevant information, it will be possible to analyse sustainable mobility in those cities.


## Structure 📂

The repository is divided into several folders containing the following files:

- **Folder data:**
   - It contains the raw data and the cleaned files which are used to build the database.

- **Folder notebook:**
   - **API request.ipynb**: this file has the access to the air quality data on the OpenAQ Platform, as well as the data import to MongoDB.
   - **queries_cleaning_data enhancement.ipynb**: data wrangling.
   - **web scraping.ipynb**: this file is used to obtain more data.

- **Folder img:**
   - the folder to save images and memes.


## Ready, steady, go! ⛏️

**1. Extract**

Mining data from various sources:
    - *API OpenAQ*: By doing several queries all the required data was obtained.
    - *Instituto Nacional de Estadística (INE)*: it has many .csv related to passenger transport.
    - *Web scraping*: In a nutshell, web harvesting.

**2.Transform**

Process and organize extracted data so its usable.

**3.Load**

Moving transformed data to a data repository in MongoDB.

![Mondongo](https://github.com/charlieciordia/03-ETL_project/blob/main/img/Mongo.png)


## To Do's 🤓

📝 Extract more data from de API, interesting parameters such as CO2 or O3, in order to enhance our database in MongoDB.

📝 Download more data related to different transport modes.


## Libraries and resources📚
 
[Pandas](https://pandas.pydata.org/docs/) 🐼

[MongoDB Compass](https://www.mongodb.com/) 🪘

[openaq](https://openaq.org/) 🌬️

[INE](https://www.ine.es/index.htm) 📈
