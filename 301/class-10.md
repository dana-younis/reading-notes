#  In memory storage

## Understanding the JavaScript Call Stack

* 1.What is a ‘call’?
* 2.How many ‘calls’ can happen at once?
* 3.What does LIFO mean?
* 4.Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
* 5.What causes a Stack Overflow?


## JavaScript error messages

* 1.What is a ‘refrence error?
* 2.What is a ‘syntax error’?
* 3.What is a ‘range error’?
* 4.What is a ‘tyep error’?
* 5.What is a breakpoint?
* 6.What does the word ‘debugger’ do in your code?











1- What is a ‘call’?

Its function invocation.

2- What does LIFO mean?

Last In, First Out

3- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

callStack

4- What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

5- What is a ‘refrence error’?

when you try to use a variable that is not yet declared you get this type os errors.

6- What is a ‘syntax error’?

this occurs when you have something that cannot be parsed in terms of syntax.

7- What is a ‘range error’?

When you Try to manipulate an object with some kind of length and give it an invalid length .

8- What is a ‘type error’?

This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

9- What is a breakpoint?

Its a point in the code, which will make your program stop at that point and help you debugg your code at that point.

10- What does the word ‘debugger’ do in your code?

It adds a breakpoint at that line, then you can walk through your code from that point step-by-step.

Call Stack
The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call