# Domain Modeling

* * Domain modeling is the method of constructing a computational model in code for a particular problem. A model is a definition of the different entities, their characteristics and actions, as well as the constraints that control the problem domain. An object-oriented model is a category of entity that stores data in properties and encapsulates behaviors in methods.A well-articulated domain model can check and validate different stakeholders' understanding of a particular issue. As a networking instrument, it describes a language that can be used within and across both technological and business teams.

- To define the same properties across multiple objects, use a constructor function.
- A constructor function is defined using a function expression.
- In other words, the variable EpicFailVideo is declared, and then a function with two parameters named epicRating and hasAnimals is assigned to it.
- When the function is called, the data in these parameters is stored in the this.epicRating and this.hasAnimals properties.
- These objects are stored within the parkourFail and corgiFail variables after they have been instantiated and initialized.


* * Generate random numbers
EpicFailVideo's prototype is given a generateRandom process, which is assigned a function with two parameters called min and max. The function computes and returns a random integer between min and max using both Math.floor and Math.random.

* * Calculate daily Likes
Features are allocated to the dailyLikes method in EpicFailVideo's prototype. The value of this is assigned to the viewers variable. Methods can access any property or method on the same object that called the daily Likes method by using this variable.


The weeklyLikes method on EpicFailVideo's prototype is assigned a function with no parameters. It adds the returning number of Likes to total using the + operator.

## Tables
* * table tag The table element is used to create a table.
* * The contents of the table are written out row by row. trYou indicate the start of each row using the opening tr tag.

* * The tr stands for table row. It is followed by one or more  td elements one for each cell  in that row

* * At the end of the row you use a closing /t tag. tdEach cell of a table is represented using a t element.
* * The td stands for table data.At the end of each cell you use a closing /td tag


* * Sometimes you may need the entries in a table to stretch across more than one column.The colspan attribute can be used on a th or td element and indicates how many columns that cell should run across.

* * You may also need entries in a table to stretch down across more than one row.The rowspan attribute can be used on a or element to indicate how many rows a cell
* * The key tables of contents and the first and last rows which may contain different contents are differentiated with three elements.These elements help people who use screen readers and also allow them, as you can see when you hear about CSS, to design these sections in a different way than the rest of the table. thead thead Within the thead portion should be the headings of the table. tbody tbody Within the tbody portion should be the body. tfoot tfoot The footer is inside the element tfoot

* * There are some outdated attributes which you should not use on new websites.You may, however, come across some of them when looking at older code, so I will mention them here

* * All of these attributes have  been replaced by the use of CSS.The width attribute was used on the opening table tag to indicate how wide that table should be and on some opening th and td tags to specify the width of individual cells.
* * The columns in a table need to form a straight line, so you often only see the width attribute on the first row and all subsequent rows would use that setting.


### Functions, Methods, and Object
* * CREATING AN OBJECT LITERAL NOTATION Literal notation is the easiest and most popular way to create objects.
* * Separate each property and method with a comma but not after the last value.You can also access properties using square brackets.
* * To access a property or method of an object you use the name of the object, followed by a period, then the name of the property or method you want to access.They work on objects created using literal or constructor notation.
* * an empty object called hote 1 is created using the constructor function.Once it has been created, three properties and a method are then assigned to the object.To get a better idea of why you might want to create multiple objects on the same page, .
* * constructor function defines a template for the hotels.Next, two different instances of this type of hotel object are created.The first represents a hotel called Quay and the second a hotel called Park.Having created instances of these objects, you can then access their properties and methods using the same dot notation that you use with all other objects.


* * The keyword this is commonly used inside functions and objects.Where the function is declared alters what this means.It always refers to one object, usually the object in which the function operates.
* 8 A FUNCTION IN GLOBAL SCOPE  When a function is created at the top level of a script that is, not inside another object or function, then it is in the global scope or global context.
* * The default object in this context is the window object. so when this is used inside a function in the global context it refers to the window object.Below, this is being used to return properties of the  window object . function windowSize All global variables also become properties of the window object. so when a function is in the global context, you can access global variables using the window object, as well as its other properties

* * The Browser Object Model contains  objects that represent the current  browser window or tab. The Document Object Model uses  objects to create a representation of the current page. The global JavaScript objects  represent things that the JavaScript language needs to make a model of.
* * Three built-in objects offer a different range of toois that help you write scripts for web pages. The Browser Object Model creates a model of the browser tab or window. Document Object Model is needed to access and update the contents of a web page.
* * In JavaScript, dates are stored as a number: specifically the number of milliseconds since midnight on January 1, 1970. By default, when you create a Date object it will hold today's date and the current time. If you want it to store another date, you must explicitly specity the date and time you want the object to hold. The Date object's methods can be used to set and retrieve dates and times from this Date object. The current date / time is determined by the computer's clock. If the user is in a different time zone, their day may staearlier or later than yours.