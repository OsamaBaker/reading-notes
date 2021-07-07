# Understanding the JavaScript Call Stack

1. What is a ‘call’?
> Invokes a function.

2. How many ‘calls’ can happen at once?
> One call at a time.

3. What does LIFO mean?
> Last In, First Out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
>function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

5. What causes a Stack Overflow?
> A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

# JavaScript error messages

1. What is a ‘refrence error’?
> This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

2. What is a ‘syntax error’?
>  this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. What is a ‘range error’?
> when there is an invalid length.

4. What is a ‘type error’?
> this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible

5. What is a breakpoint?
> The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

6. What does the word ‘debugger’ do in your code?
> will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values