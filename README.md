# Fetching tweets having hashtags around Adani, Hindenburg using Twitter API v2
This project contains python script for fetching tweets typically for hashtags around Adani and Hindenburg like #AdaniGroup, #AdaniGreens, #AdaniPower, #Hindenburg_Report, etc. The tweets are in both English and Hindi. After fetching the tweets, you can filter out either of the category as per the requirements.

### Installation
If you look into the file, the first cell includes all python packages necessary for the project. To install them, you simply need to run the cell.

### Credentials
Log onto Twitter Developer Portal. After completing all formalities, create an app and generate your API tokens, etc. You can simultaneously create multiple apps and generate individual credentials for each of them. On the developer console, you can also have a look on the daily API calls you have made and the daily limits. Save the key in a json file named twitter_credentials.json.

### Enjoy fetching data from the API
The script also involves handling the complex json response received from the Twitter server, structurizing the data into a table and storing the table in CSV file.
