# VoC-streamlit-app
This repository is to host a streamlit app for Voice of Customer Analysis

There are two ways to use this repository - 

### Method 1: Access Deployed Dashboard

Refresh ['this link'](https://share.streamlit.io/app/nivii26-voc-streamlit-app-visualize-9xla2m/) for an updated dashboard.

### Method 2: LocalHost
#### Set-up
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

Ensure local working directory is 'VoC-streamlit-app'

Replace the 'final_lsa.csv' in the repository with the desired file to generate the dashboard. 

The csv file should contain the following columns = ['Sentiment', 'Time', 'Tokenized_text', 'Main Topic']. Ensure that the column names are the same, and that the file name is 'final_lsa.csv'.

Note : Order of columns doesn't matter and presence of extra columns is also okay!

To generate dashboard using localhost, run the following command on your terminal - 
```
run streamlit visualize.py 
```
# Dashboard Demo
 <img width="749" alt="image" src="https://user-images.githubusercontent.com/79890811/231934552-6975338a-a297-4048-9a44-ed72c8f4da01.png">
 <img width="775" alt="image" src="https://user-images.githubusercontent.com/79890811/232048871-f1f162ce-25b2-49fb-a0d0-65b24a94ec8c.png">
 <img width="763" alt="image" src="https://user-images.githubusercontent.com/79890811/231934687-ea0f4e9b-885f-4ac4-9f0e-3b7889aa9897.png">
 <img width="649" alt="image" src="https://user-images.githubusercontent.com/79890811/231935482-e7d4be8d-4156-4c99-9264-79b49e6e4352.png">
 <img width="675" alt="image" src="https://user-images.githubusercontent.com/79890811/231935546-920ef945-d71d-4e51-9b2e-9e4ac0b4d44c.png">
 <img width="682" alt="image" src="https://user-images.githubusercontent.com/79890811/231935739-04c8315e-dcf8-4dfa-9034-85940e281404.png">
 <img width="691" alt="image" src="https://user-images.githubusercontent.com/79890811/231935904-ea9a76a1-3516-4801-af6f-934504d92b00.png">





