# Survey App With Java Servlet
A simple survey app using java servlet. 
In this app there is a servlet that handle get and post request for getting survey data and voting in survey. The request and response are in json format.
There is also a html file that offer a simple UI to vote from the browser.
The question and options for the survey are written in the survey.txt and can be changed, 
but there should be at least question and 2 answers.

## Run this app with apache tomcat 9:
If you don't have apache tomcat 9 yet you can download it from here.
Download this project and unzip it, then move it under the webapps folder in apache home.
Start apache server. You can do it by running startup.sh (for bash) or startup.bat (for cmd), both under bin folder in apache home.
Go to your browser and go to http://localhost:8080/surveyApp/index.html and see the survey page.
