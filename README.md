# VoC-streamlit-app
This repository is to host a streamlit app for Voice of Customer Analysis

### Set-up
Create a virtual environment
```
virtualenv streamlit_venv
```

Activate the virtual environment
```
source venv/Scripts/activate
```

Install the packages in requirements.txt
```
pip install -r requirements.txt
```

Clone this repository
```
$ git clone https://github.com/nivii26/VoC-streamlit-app.git
```

There are two ways to use this repository - 

### Method 1: Access Deployed Dashboard

Refresh ['this link'](https://share.streamlit.io/app/nivii26-voc-streamlit-app-visualize-9xla2m/) for an updated dashboard.

### Method 2: LocalHost
Ensure local working directory is 'VoC-streamlit-app'

Replace the 'final_lsa.csv' in the repository with the desired file to generate the dashboard. 

The csv file should contain the following columns = ['Sentiment', 'Time', 'Tokenized_text', 'Main Topic']. Ensure that the column names are the same, and that the file name is 'final_lsa.csv'.

Note : Order of columns doesn't matter and presence of extra columns is also okay!

To generate dashboard using localhost, run the following command on your terminal - 
```
run streamlit visualize.py 
```

