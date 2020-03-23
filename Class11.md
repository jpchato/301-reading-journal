# EJS
* Evaluate an injected variable, iterate/loop over an array, if/else statements, layouts, partials
* `npm init -y`, `npm install --save express body-parser cors ejs`, 
* It appears to be a library
* `index.ejs`
* It takes the name of the file and not the file path
* Creating instance of server, configuring server, set views folder to handle views being created, view engine is set to ejs, get route for root directory, app to listen on 8000
* ejs symbols `<%= xyz %>`, can pass almost anything you want inclduing arrays
* `<% for (var person of people) {<%=person.name %>}>`
* `<% if(person.name) === 'dave' { %> <%= this is definitely that dave %>`
* So pretty much every line gets `<% %>`