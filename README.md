# YouTube Data Harvesting and Warehousing

## Overview

This project is a Python script designed for collecting and storing YouTube channel data into both MongoDB and PostgreSQL databases. The collected data includes channel information, playlist details, video information, and comments.

## Prerequisites

Make sure you have the following installed before running the script:

- Python
- MongoDB
- PostgreSQL
- Required Python packages (can be installed using `pip install -r requirements.txt`)
  
1.Install the required packages:
pip install -r requirements.txt

2.Update the API key:
Replace the placeholder API key in the script with your actual YouTube API key.

3.Run the script:
python main_script.py

4.Access the Streamlit interface:

After running the script, you can use the Streamlit interface to interact with the collected data.

5.Migrate data to SQL:

Click the "Migrate to SQL" button in the Streamlit interface to transfer the collected data to a PostgreSQL database.
