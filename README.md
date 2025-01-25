# AnsibleHealth

Brief description:
Created a Python script running in Google Colab that converts the provided markdown meeting notes into a well-formatted Google Doc.

Setup instructions:
    1) Open google cloud console 
    2) Create a project
    3) Go to APIs and Services
    4) Enable google docs API
    5) Go to credentials and add credentials for OAuth client Id
    6) Complete all the steps and obtain the credentials 

Required dependencies:
    Required to install python libraries related to google-auth
    1) pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client markdown
    
How to run in Colab:
    1) Do the setup and download all the dependencies 
    2) Upload or give the path of content.md correctly in the script
    3) Run the python Script and click on the link to access the document
