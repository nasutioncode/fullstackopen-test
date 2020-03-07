title Add New Note Process

Browser->Server: https://fullstack-exampleapp.herokuapp.com/notes
note right of Browser: 
Receive text/html file
after that notify status of POST method
end note
Server-->Browser: HTML-codes
note over Browser:
Redirect with header page location
end note
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/notes
Server-->Browser: HTML-code
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.css
Server-->Browser: main.css
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.js
Server-->Browser: main.js
note over Browser:
javascript get data.json with ajax
end note
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/data.json
note over Browser:
the data.json with new value was added by submitted form
end note
Server-->Browser: [{content: "HTML is easy", date: "2020-03-07T09:44:10.911Z"},…]
note over Browser:
The browser executes the event handler, then displays a new note
end note

