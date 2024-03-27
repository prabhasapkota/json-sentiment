# Module 4: Requests, JSON, and basic NLP with spaCy

## Author: Prabha Sapkota Pokharel

### Objectives:
This exercise illustrates how to access web-hosted APIs, get back a response in JSON Links to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many and they change. The skill skills are being able to :
(a) make an API request 
(b) find the information we need in the returned response. 

### How to Get Started?
#### Task 1:
1. Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner.  The base repository is available at: https://github.com/wmnlp-materials/json-sentiment Links to an external site.
2. Clone YOUR new repo down to your machine.

### TO DO THINGS:
Create and activate a virtual environment. Run the following commands to install these into your virtual environment:

python -m pip install requests
python -m pip install spacy
python -m pip install spacytextblob

### Check in everything is set up:
Add the following code to the first Python code cell. Run the cell. 
# Create and activate a Python virtual environment. 
# Before starting the project, try all these imports FIRST
# Address any errors you get running this code cell 
# by installing the necessary packages into your active Python environment.
# Try to resolve issues using your materials and the web.
# If that doesn't work, ask for help in the discussion forums.
# You can't complete the exercises until you import these - start early! 
# We also import json and pickle (included in the Python Standard Library).

import json
import pickle

import requests
import spacy
from spacytextblob.spacytextblob import SpacyTextBlob

print('All prereqs installed.')
!pip list

If you just see the print statement - congratulations! You have successfully installed everything and are ready to practice applying these powerful tools!

#### Task 2: Open Notebook and Complete Tasks 
1.On your machine, open the Jupyter Notebook for editing. 
2.Required: In your Markdown introduction, add a viewable, clickable link to your GitHub repo after your name. Build your brand and make your Markdown introduction clear and professional. 
3.Required: Use Markdown headings  (e.g. Question 1) to clearly show your content by each question number. 
4.Complete the first task.
5.Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
6.Complete the second task.
7.Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
8.Work this way until all tasks have been completed. 

#### Task 3: Export to HTML and Finalize Repo
1.Execute each notebook.
2.After executing, export each notebook to HTML.
3.Commit and push your HTML files to your GitHub repo along with the executed notebooks. 
4.Verify you have a professional README.md that introduces your GitHub repository and provides helpful information about your project.

#### Requirements

1.Markdown introduction with name and clickable link is required.
2.Markdown Section Headings for each Question are required. 
3.Execute your code before exporting HTML and pushing notebooks. (See FAQ for help.)  
4.Unexecuted code is not eligible for credit.

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts
