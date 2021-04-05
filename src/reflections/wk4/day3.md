Day 3

Daily Challenge

Read Asynchronous Code > Async and Await and answer the following questions

What is the purpose of Async/Await?
>Async/await were introduced to solve the complex syntax issue that was introduces with Promises. They make the code look like its sychronous when  in reality it is asynchronous and non-blocking behind the scenes.

What must you do in order to await a promise inside of a function?
>When you want to call this function you prepend(attach a piece of data to the beginning of another) await, and the calling code will stop until the promise is resolved or rejected. Prepending the async keyword to any function means that the function will return a promise.
Even if it's not doing so explicitly, it will internally make it return a promise.

What are some of the primary benefits of Async/Await?
>Async functions can be chained very easily, and the syntax is much more readable than with plain promises. Debugging inside of promises is hard because the debugger will not step over async code. Async/await makes this very easy because to the compiler it's just like synchronous code.