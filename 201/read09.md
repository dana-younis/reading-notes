# Forms 
* * forms  allow users to perform other functions online.You will see forms when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists.

* * How Forms Work A user fills in a form and then presses a button to submit the information to the server.The name of each form control is sent to the server along with the alue the user enters or selects.The server processes the information using a programming language It may also store the information in a database
* * A form may have several form controls, each gathering different information.
The server needs to know which piece of inputted data corresponds with which form element To differentiate between various pieces of inputted data, information is sent from the browser to the server using name/value 
* * The name/value pairs sent to the server are:You should never change the name of a form control in a page unless you know that the code on the server will understand this new value. username=IvyIf the form control allows the user to enter text, then the value of the form control is whatever the user has typed in. vote=HerbieIf the form control allows you to choose from a fixed set of answers the web page author will add code that gives each option an automatic value.
* * Form validation is the process of checking a form is filled in correctly before it is sent to the server. Traditionally, form validation has been performed using JavaScript. HTML5 is introducing validation and  leaving the work to the browser.

## Lists, Tables & Forms
* * You can specify an image to act as a bullet point using the list-style-image property. The value starts with the letter urls  and is followed by a pair  of parentheses.Inside the parentheses, the path to the image is given inside double quotes
* * Lists are indented into the page  by default and the list-styleposition property indicates whether the marker should oppear on the inside or the outside of the box containing the main points.
* * This property can take one of two values:
- outsideThe marker sits to the left of the block of text.
- insideThe marker sits inside the box of text which is indented

* * A table is a set of several properties that are commonly used with tables. These properties can be put together to make a single table example. The properties include width, padding, text-transform, color and border-top, border-bottom and background-color. The table example uses the following properties: width, space, padding and text- transform.

* * The border-spacing property allows you to control the distance between adjacent cells. The value of this property is usually specified in pixels. It is possible to collapse adjacent borders to prevent this using the border-collapse property. The width of the border would be twice that of the outside edges if two cells meet, and the width of lines would be double if two lines meet.
 
* * Labels for form elements are often different lengths, which means that the form controls will not appear in a straight line.In form, each topic we ask  about is placed inside a div element to ensure that each question appears on a line. It is easier for users to fill in a form if the form controls are aligned in a straight vertical line. The CSS on the opposite page addresses this.

* * Each row of the form has a title telling users what they need to  enter. We can use a property called  float to move the titles to the left of the page. Styles are also applied to the  div elements that contain each row. The submit button is also aligned to the right of the title. The text-align property is used to align the titles and submit buttons.

### EVENTS

* * When an event occurs, the event object tells  you information about the event, and the  element it happened upon. Every time an event fires, the  event object is passed to any function that is the event  handler or listener. The event object contains helpful data about the events that happened. Some  proprietary programmers also use the  proprietary parameters e to refer to the  error object; so e may mean  event or error in some script s.
* * The event object is passed to the event listener. The code includes fallbacks for IES-8. In order to determine which function to use, the function uses the event object's target property. The function check Length can be used on any text input.

* * Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element. If you place the event listener on the u1  element rather than the 1i  element,  you only need one event listener. This gives better performance, and if you add or remove items from the list it would still work the same. You are only responding to one event handler for each child element.
* * When calling a function, the event object's target property is the best way to determine which element the event occurred on.But you may see the approach below used; it relies on the this keyword.
 * * USING PARAMETERS If you pass parameters to the function, the this keyword no  longer works because the owner of the function is no longer the element that the event listener was bound to, it is an anonymous function You could pass the element the event was called on as another parameter of the function.
* *  load event is usually used to trigger scripts accessing page contents. A function named in this example config gives text emphasis. When you have loaded the tab, input. Can INFORMANCE setup function var text-based information; The event will be elevated automatically by the object of a window.
* * The aim of this example is to use  the c1ick event to remove the  big note that has been added to  the middle of the page. But first, the script has to create that note. This function  will remove the note that was  added by the same script. The function  is called JAVAScriptT.
* * Binding is the process of stating which event you are waiting for. When an event occurs on an element, it can trigger a JavaScript function. The most commonly used events are W3C DOM events, although there are others in the HTMLS  specification. You can use event delegation to monitor for events that happen on all of the children of an element.