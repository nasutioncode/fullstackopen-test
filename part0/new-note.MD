![new_note] 
https://www.websequencediagrams.com/cgi-bin/cdraw?lz=dGl0bGUgQWRkIE5ldyBOb3RlIFByb2Nlc3MKCkJyb3dzZXItPlNlcnZlcjogaHR0cHM6Ly9mdWxsc3RhY2stZXhhbXBsZWFwcC5oZXJva3VhcHAuY29tL25vdGVzCm5vdGUgcmlnaHQgb2YgAEkHOiAKUmVjZWl2ZSB0ZXh0L2h0bWwgZmlsZQphZnRlciB0aGF0IG5vdGlmeSBzdGF0dXMgb2YgUE9TVCBtZXRob2QKZW5kIG5vdGUKAIETBi0tPgBSCUhUTUwtY29kAHUIb3ZlcgBwCQpSZWRpcmVjdCB3aXRoIGhlYWRlciBwYWdlIGxvY2F0aW9uAFIKAIFtEUhUVFAgR0VUAIFVMgCBDBsAIUZtYWluLmNzAFYUABIJAB9KagBPGWoAgmEVamF2YXNjcmlwdCBnZXQgZGF0YS5qc29uAIMABmFqYXgAgidPAFkJAINwFHRoZQBzEG5ldyB2YWx1ZSB3YXMgYWRkZWQgYnkgc3VibWl0dGVkIGZvcm0AhFocW3tjb250ZW50OiAiSFRNTCBpcyBlYXN5IiwgZGF0ZTogIjIwMjAtMDMtMDdUMDk6NDQ6MTAuOTExWiJ9LOKApl0AhRkUVGhlIGIAhn0GIGV4ZWN1dGVzIHRoZSBldmVudCBoYW5kbGVyLCB0aGVuIGRpc3BsYXlzIGEAgUkFAIYZBQCGHgkK&s=default

### The raws of code from image ###
```
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

```

