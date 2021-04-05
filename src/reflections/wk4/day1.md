Day 1

Daily Challenge

Read Asynchronous Code > Callback Hell and answer the following questions

What are some of the signs and causes of Callback Hell?
>The pyrimid shape in the code is a sign of Callback Hell and is caused when people try to write JavaScript in a way where execution happens visually from top to bottom.

What does the asynchronous mean and how are callbacks involved?
>Callbacks are just a convention rather than a special thing called a callback. All that means is that functions that use Callbacks take time to produce a result. 'Asynchronous', aka 'async' just means 'takes some time' or 'happens in the future, not right now'. Callbacks are generally only used when doing I/O (Input-output systems transfer information between computer main memory and the outside world), e.g. downloading things, reading files, talking to databases, etc.

Summarize the 3 ways to avoid / fix Callback Hell. 
> One was to avoid Callback Hell is to "keep your code shallow", which just means to be sure youre naming all of your functions clearly instead of nesting them to avoid confusion. Once you give then names place them at the top level of your program
Use function hoisting to your advantage to move functions 'below the fold'. Handle every single error in every one of your callbacks. Use a linter like standard (opens new window)to help you with this. Another way is to
create reusable functions and place them in a module to reduce the cognitive load required to understand your code. Splitting your code into small pieces like this also helps you handle errors, write tests, forces you to create a stable and documented public API for your code, and helps with refactoring.