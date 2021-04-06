# Error Handling & Debugging

* * ORDER OF EXECUTIONTo find the cause of an error, it helps to know how scripts are processed.The sequence of statements can be complex; some tasksUnable to complete before another declaration or function is executed
* * The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 
* * In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Functions in JavaScript are said to have lexical scope. They are linked to the object they were defined within.
* * If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. If the error is not handled, the script will stop processing and the user will not know why. 
* * SYNTAX IS NOT CORRECT This is caused by incorrect use of the rules of the language.It is often the result of a simple typo.Reference Error VARIABLE DOES NOT EXIST This is caused by a variable that is not declared or is out of scope.
* * : DEBUG THE SCRIPT TO FIX ERRORS If you come across an error while writing a script or when someone reports a bug, you will need to debug the code, track down the source of the error and fix it.
* * You will find that the developer tools available in every major modern browser will help you with this task.
* * Sometimes, an error may occur in the script for a reason beyond your control.
* * If you are stuck on an error, many programmers suggest that you try to describe the situation (talking  loud) to another programmer. This seems to be an effective way of finding errors in all programming languages. Use tools to write messages to the console to tell how far your script has executed. Use breakpoints to pause execution and inspect values that are stored in variables. If  nobody else is available, try describing it to yourself.


* * Once you know the rough area  in which your problem is located, you can then try to find the actual line of code that is causing the error. If the problem is hard to find, it is easy to lose track of what you have and have not tested. No matter how stressful the circumstances, if you can stay calm and methodical, the problem will feel less overwhelming and you will solve it faster. If you can't find the problem, you may have to repeat the whole process.
* * To differentiate between the types of messages you write to the console, you can use three different methods.They use various colors and icons to istinguish them.
*STEPPING THROUGH CODE*
* * hen you have set breakpoints, you will see that the debugger lets you step through the code line by line and see the values or variables as your script progresses.When you are doing this, if the debugger comes across a function, it will move onto the next line after the function.It does not move to where the function is defined

* * This behavior is sometimes called stepping over a function, it is possible to tell the debugger to step into a function to see what is happening inside the function.

* * You can create a breakpoint  in your code using just the  Debugger keyword. When developer tools are open, this will automatically create a  breakpoint. It is important to remove these statements before your code goes live as this could stop the page running.
* * Bad data might not cause an error straight away, but it could cause a problem later on. In such cases, it helps to report the problem straight away. It can be much harder to find the source of the problem if the data causes an error in a different part of the script.
* * If you use a string in a mathematical operation that does not get an error, you get a special value called NaN. By checking that the results  are numeric, the script can fail  at a specific point and you can provide a detailed error about the problem.
* *  If you understand execution contexts (which have two  stages) and stacks, you are more likely to find the error in your code. JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description.
 