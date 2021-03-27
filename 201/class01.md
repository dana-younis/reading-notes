# How the Web Works
* * initially we contact the ISP to write the website, our computer is connected to the DNS which tells our computer the IP This ip that the dns server returns to our computer allows our browser to connect to the web server that is hosting the website that is I requested 
* * now lets talk about how we can entering things using html

- Writing Links   by using <a> 

## Structure

* * tags,characters that sit inside angled brackets to give the information they surround special meaning.
* * HTML uses tags 
 * Tags comes with
 * opening tag,tell us more about the content of that element
 * closing tag


* * the elements of html
* html.body,h1 *This is the Main Heading*,p*introduction to the rest of  the page* ,h2*This is a Sub-Heading*


### Extra Markup
* *  The id and class attributes allow you to identify particular elements,their purpose,The class attribute on any element can share the same value. 
* * DOCTYPES tell browsers which version of HTML you are using,the use of a DOCTYPE can also help the browser to render a page correctly.
* * The <div> and <span> elements allow you to group block-level and inline elements together,span can control the appearance of the content of these elements using CSS,div makes it easier to follow your code if you have used .
* * iframes cut windows into your web pages through which other pages can be displayed
* * The meta tag allows you to supply all kinds of information about your web page.The meta element uses the http-equiv and content attributes in pairs, specify a description for the page
* * Escape characters are used to include special characters in your pages ,When using escape characters, it is important to check the page in your browser to ensure that the correct symbol shows up


#### HTML5 LAYOUT
* * The new HTML5 elementsindicate the purpose of different parts of a web page and help to describe its structure,If they do not have JavaScript enabled then they will not be able to see the content of these HTML5 elements,allow us to create rules that target those elements.The new elements provide clearer code compared with using multiple div elements,To make HTML5 elements work in Internet Explorer 8 and older versions of IE,extra JavaScript is needed, which is available free from Google.


##### PROCESS & Design
 - It's important to understand
 - who your target audience is,
 - why they would come to your site
 - what information they want to find 
 -  when they are likely to return.
 
* * Site maps allow you to plan the structure of a site. create a diagram of the pages that will be used to structure the site.
* * To help you decide what information should go on each page, you can use a technique called card sorting.
* * Wireframes is a simple sketch of the key 
information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require,you can ensure that all of the information that needs to be on a page is included,make design easier because you know what information needs to appear on which page before considering how the the page should look
* * You can differentiate between pieces of information using size, color, and style.  
* *  grouping and similarity to help simplify the information you present,Grouping related pieces of information together can make a design easier to comprehend. 



###### THE ABC OF PROGRAMING
* * JavaScript files are text files have the . j s extension. 
* * The HTML script element is used in HTML pages to tell the browser to load the JavaScript file (rather like ,To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it,the high level view of the tasks can be represented using a flowchart
A script is a series of instructions that the computer can follow in order to achieve a goal. Each time the script runs, it might only use a subset of all the instructions. Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.


- change the content of an HTML page using JavaScript 
 - RECEIVE A PAGE AS HTML CODE 
 - CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY
 - USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN


* *  Computers create models of the world using data. The models use objects to represent physical things. Objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object évents which are triggered when a user interacts with the computer
* * Web browsers use HTML markup to create a model of the web page. Each element creates its own node which is a kind of object
 
* * When you want to use JavaScript with a web page, you use the HTML script element to tell the browser it is coming across a script. Its sre attribute tells people where the JavaScript file is stored

* * The HTML script element is used in HTML pages to tell the browser to load the JavaScript file rather like the link element can be used to load a CSS file. If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created. 