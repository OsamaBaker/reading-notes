# Read10

## Debugging

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:
function greetUser () {
O return 'He 11 o ' + getName ();
0
function getName() {
var name= 'Molly ' ;
return name;
_, var greeting= greetUser();
e al ert(greeting);
This script above creates a greeting message, then
writes it to an alert box (see right-hand page). In
order to create that greeting, two functions are used:
greetUser () and getName () .
You might think that the order of execution (the
order in which statements are processed) would be
as numbered: one through to four. However, it is a
little more complicated.
To complete step one, the interpreter needs the
results of the functions in steps two and three
(because the message contains values returned by
those functions). The order of execution is more like
this: 1, 2, 3, 2, 1, 4.
8 ERROR HANDLING & DEBUGGING
1. The greeting variable gets its value from the
greetUser() function.
2. greetUser() creates the message by combining
the string 'He 11 o ' with the result of getName ().
3. getName () returns the name to greetUser().
2. greetUser() now knows the name, and combines
it with the string. It then returns the message to the
statement that called it in step 1.
1. The value of the greeting is stored in memory.
4. This greeting variable is written to an alert box.

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code

WHERE IS THE PROBLEM?
First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.
1. Look at the error message, it tells you:
• The relevant script that caused the problem.
• The line number where it became a problem for
the interpreter. (As you will see, the cause of
the error may be earlier in a script; but this is the
point at which the script could not continue.)
• The type of error (although the underlying cause
of the error may be different).
2. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.
3. Use breakpoints where things are going wrong.
They let you pause execution and inspect the values
that are stored in variables. 