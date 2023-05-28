<div align="center">
      <h1> <br/>Google Calendar API OAuth 2.0 for Web Server Applications Integration - Django Rest Framework</h1>
     </div>


# Description
Problem: In this assignment you have to implement google calendar integration using django rest api. You need to use the OAuth2 mechanism to get users calendar access. Below are detail of API endpoint and corresponding views which you need to implement

# Features
For run this project on a local machine:

Create virtual environment
https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

pip install - r requriments.txt
Endpoint:
/rest/v1/calendar/init/ -> google_calendar_init_view()
This view should start step 1 of the OAuth. Which will prompt user for his/her credentials

/rest/v1/calendar/redirect/ -> google_calendar_redirect_view()


This view will do two things

Handle redirect request sent by google with code for token. You need to implement mechanism to get access_token from given code
Once got the access_token get list of events in users calendar
Note: To run this assignment need google account credentials which need to save in the project directory and add a redirect URL in your google cloud. Please read below documents and references section.
Documents and References
Name	Sources
Google Identity: Using OAuth 2.0 for Web Server Applications	/identity/protocols/oauth2/web-server
Google Calendar API	/calendar/api/v3/referenc
Google Account Credentials	/identity/protocols/oauth2/web-server#exchange-authorization-code

# Tech Used
 ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
      

