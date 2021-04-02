Day 4

Daily Challange

Read Advancing with JS > The Observer Pattern and answer the following questions

What problems does the Observer Pattern seek to solve? 
> Observer pattern is used when there is one-to-many relationships between objects such as if one object is modified, its depenedent objects are to be notified automatically. 

What are the three mechanisms of the observer pattern?
>Subscribe which adds new observable events, unsubscribe which removes observable events, and
broadcast which will execute all events with bound data.

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
> The bcw-template uses the MVCS to connect to the dom and share responsibility with other files. Proxy objects are housed in the AppState where all data is stored and the Proxy acts as a copy for all data that is then passed into the other files who import it. The observer patten is set to watch for changes to the Proxy object and then ones a change occurs initiates the draw function to then render the information onto the DOM.