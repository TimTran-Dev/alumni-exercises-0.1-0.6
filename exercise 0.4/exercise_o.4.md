## Part 0 - Exercise 0.4 - New Note

**Exercise Problems:**[Full Stack Open Link To Exercises 0.1-0.6](https://fullstackopen.com/en/part0/fundamentals_of_web_apps#exercises-0-1-0-6)

---

**user->browser:** 

**note over browser:**<br/>
user inputs a note inside of form<br/> 
and submits the input<br/>
**end note**<br/>

**browser->server:** HTTP POST https://studies.cs.helsinki.fi/exampleapp/notes<br/>

**note over server:**<br/>
server receives request from the browser<br/> 
to add a note to the database<br/>
**end note**<br/>

**server-->browser:** URL redirect to https://studies.cs.helsinki.fi/exampleapp/notes

**note over browser:**<br/>
server adds note to the database<br/> 
and re renders the web page with the new notes added<br/>
**end note**<br/>

**browser->server:** HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes<br/>
**server-->browser:** HTML-code<br/>
**browser->server:** HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css<br/>
**server-->browser:** main.css<br/>
**browser->server:** HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js<br/>
**server-->browser:** main.js<br/>

**note over browser:**<br/>
browser runs JavaScript to<br/>
request for content in data.json<br/>
**end note**<br/>

**browser->server:** HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json<br/>
**server-->browser:** [{ content: "HTML is easy", date: "2020-11-9" }, ...]<br/>

**note over browser:**<br/>
browser runs the event handler to display<br/> 
the notes on the webpage<br/>
**end note**<br/>

----
**Resource:** [Link to Web Sequence Diagram Resource](https://www.websequencediagrams.com/)
