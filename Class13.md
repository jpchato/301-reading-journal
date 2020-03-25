# Sending Form Data
* action and method
* the action attribute defines where the data gets sent. 
* the method attribute defines how data is sent
* GET and POST are two common methods
* the GET method is used by the browser to ask the server to send back a given resource
* the POST method is the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request
  * data is not appended to the URL (secret)
* Sending form data can be easy but securing that data is not. 
* If you need to send a password, never use the GET method
* If you need to send a large amount of data use the POST method
* Be paranoid and never trust users
  * escape potentially dangerous characters
    * things to watch out for are character sequences that look like executable code
  * limit the incoming amount of data to allow only what's necessary
  * sandbox uploaded files
    * store uploaded files on a different server