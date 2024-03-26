Project Title YouTube Data Harvesting and Warehousing using MySQL, Python and Streamlit

Problem Statement: 
The problem statement is to create a Streamlit application that allows users to access and analyze datas of multiple YouTube channels. 

The application should have the following features: 
1.Ability to input a YouTube channel ID and retrieve all the relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes, comments of each video) using Google API. 2.Ability to view the collected data from the Youtube API. 3.Option to store the retrieved data in a MYSQL database in table respective table. 4.Ability to view the tables and table data from the SQL database. 5. View the SQL queries for the given statements.

Approach: Set up a Streamlit app: Streamlit is a great choice for building data visualization and analysis tools quickly and easily. You can use Streamlit to create a simple UI where users can enter a YouTube channel ID, view the channel details, and select channels to migrate to the data warehouse. Connect to the YouTube API: You'll need to use the YouTube API to retrieve channel and video data. You can use the Google API client library for Python to make requests to the API. I have used MySQL as the database for this project. Write SQL queries
to create, insert and select data from Database. We can use a Python SQL library such as mysql.connector to interact with the SQL database with SQL queries. Finally, with the help of
Streamlit app you can display the retrieved data. Overall, this approach involves building a simple UI with Streamlit, retrieving data from the YouTube API, storing it in MySQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app.
