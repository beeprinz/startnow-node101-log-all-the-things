The prompt for this project is the following:

In this project you will build your own custom logger that will log some information about each request it recieves. You will also expose an endpoint on the server so it would be easy for anyone to retieve the latest log data from the web.

Write the code so your server will return "ok" to the visitor (you don't need to actually serve up a webpage) and respond with 200 status code

Every request to your server must be logged to the console
Every request to your server must be logged to a file
The log file is named log.csv and must be csv format
Expose an endpoint (does not require authentication) http://localhost:3000/logs that will return a json object with all the logs