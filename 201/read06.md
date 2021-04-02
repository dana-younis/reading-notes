#  Object Literals 
* * Properties and methods have a name and a value, including variables and named functions. The name is considered a key in an entity. There cannot be two keys of the same name for an entity. This is how keys are used to control the values. A property may be a
- string,
- number, 
- boolean,
- sequence, 
- object.
* *  Objects consist of a series of pairs between name and meaning but the names are referred to as keys.

* * The most simple and common way to construct objects is to create a literal notation. The object is the curly braces and their contents. There are many ways to construct the objects. The object is contained in a hotel variable, so you can call it a hotel object. Use a colon to separate each key from its value. Trim any property and process with a comma but not after the last value

* * Dot notation is used to access an object's properties or methods.


* * Square brackets may also be used to access objects. To access a property or method of an object, type the object's name, followed by a time, and then the name of the property or method you want to access. This is referred to as dot notation. The time is referred to as the member operator. The property or function on the right is a part of the entity on the left. In this case, two variables are generated to carry the hotel name and the number of available rooms. 

* * To invoke the function, type the object name followed by the method name.


* * If you had two objects on the same tab, you'd build them both with the same notation but store them in variables with different names.

## Chapter 5: “Document Object Model” (pp.183-242
* * A blueprint of a web page is created when a browser loads it. The model is known as a DOM tree, and it is stored in the memory of browsers.

* *  attribute, and piece of text in HTML has its own DOM node. A document node is added to the tree's top; it represents the entire page. You navigate to any feature, attribute, or text node via the document node. It serves as the starting point for all DOM tree visits.
* * The layout of an HTML page is defined by HTML elements. The h l TO h6 elements indicate the sections are headings; the p tags indicate where paragraphs of text begin and end; and so on.) To gain access to the DOM tree, begin by searching for elements. If you've found the feature you're looking for, you can navigate to its text and attribute nodes if necessary. This is why you can begin by studying methods for accessing entity nodes before learning how to view and modify text or attributes.

* * There are two steps to accessing and editing the DOM tree:
- Find the node that corresponds to the element you want to deal with.While the terms elements and element nodes are interchangeable, when the DOM is said to be working with an element, it is simply working with a node that represents the element.

- Make use of its text, child components, and attributes.

* * To have entry to a single element or a part of the page contained within that single element. Other times, you would want to pick a set of element s, such as every hl element on the page or every 1 I element in a specific list.

* * The DOM tree depicts the body of the list example's tab. We prioritize accessing elements, so it only displays element nodes. The diagrams on the following pages show the elements will be returned by a DOM query. Bear in mind that entity nodes are the DOM representation of an entity.

* Given the value of its I d attribute, selects an individual feature.
To be selectable, the HTML must have an id attribute.

* CSS selector makes use of CSS selector syntax to select one or more components.
This method only returns the first matching variable.

* * Both getElementById  and querySelector  will scan and return individual elements from a text. Both use the same syntax. Since no two elements can have the same value for their 1d attribute, getElementByld is the fastest and most powerful way to access an element. This method's syntax is seen below, and an example of its use is seen on the page to the right. Since querySelector  is a more recent update to the DOM, it is incompatible with older browsers. However, since its parameter is a CSS selector, it can be used to precisely target a much larger number of components.

* * If a DOM query returns a Nodelist, you can use it.
will like to:
* Choose an element from the NodeList.
* Iterate through each object in the NodeList and
apply the same claims to each of the
nodes of an element

* * Nodelists have a method called item that returns a single node from the Node list. As a function parameter, you determine the index number of the desired variable inside the parentheses.


*  Choose elements with a cl ass attribute with the value hot and save the Nodelist in a vector called e 1 ements.
*  To find out how many elements were uncovered, use the 1 ength property. If one or more are detected, the code in the if statement is executed.
* In a variable named fi rstitem, store the first element from the Node List. Since index numbers begin at zero, it says 0.

* * Since it is simpler, array syntax is favoured over the I tem  process. Check if a NodeList includes nodes before choosing one. If you use the NodeList often, save it in a variable. SYNTAX OF AN ARRAY Person nodes can be accessed using a square bracket notation equivalent to that used to manage other nodes.
* *  If, as in all DOM questions, If you need to view the same NodeList many times, store the output of the DOM query in a Nodelist as seen below, but there are no matching objects, individual items from an array. The variable would be null and void. List of nodes.

* * hotItems is a vector that includes The Array syntax's length property is used to denote which object in the Nodelist is selected. Nodelist means the number of elements in the NodeList. It contains all that is actually being focused on: hotItems It makes use of the counter variable, which is enclosed in square brackets. List objects with the class attribute set to hot. The querySelectorAl1 method is used to obtain the number of objects. determines how many times the loop should be executed

* * The innerHTML property and DOM manipulation are two somewhat different ways to inserting and extracting content from a DOM tree. THE innerHTML PROPERTY is a kind of HTML property. It should be remembered that there are security threats involved with using innerHTML. METHODOLOGY innerHTML can be used on any element node for ADDING CONTENT and Deleting CONTENT. It can be used to both retrieve and overwrite information. When an element is updated, new material is supplied as a string.

* * The most fundamental security is to discourage users from inserting characters that they do not need to use when providing the type of information into form fields.

* * All user-generated material containing characters used in code should be escaped on the server. Any markup attached to the website must be under your authority.

* * ESCAPING USER CONTENT 
Until being shown on the website, all data from untrusted sources should be escaped on the server.
Most server-side languages provide helper functions for removing or escaping malicious code.

* * A DOM tree is used by the browser to display the page. Document nodes, element nodes, attribute nodes, and text nodes are the four kinds of nodes in DOM trees. You can choose entity nodes based on their id or cl ass attributes, tag name, or CSS selector syntax. 
* * A Nadel I st is always returned when a DOM query will return more than one node. You can view and edit an entity node's content using properties like textContent and innerHTML, as well as DOM manipulation techniques. An entity node may have several text nodes and child elements that are siblings. The DOM implementation in older browsers is inconsistent.

