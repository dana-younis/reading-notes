# Event Driven Applications


# Review, Research, and Discussion

Why is access control important?
To offer multiple degrees of access to the users to the app data in which may be more secure and decrease the dangers on the web app data.


Describe an application that would need access control.?
Companies employ applications or company registrations, which should allow every user to access only restricted corporate data and take various measures.


What is a role used for?
The Role used in the RBAC to define each user access authority based on their role in the company.


Why is role based access control more scalable than discretionary or mandatory access control?
Because MAC is the most stringent of all control levels and the system administrator's control setting. And DAC provides users with access based on their identification or groups. During RBAC, we provide people access depending on their functions and over time, while changing their group easily, we may alter their position in the organization. Also over time the ALC unit may be updated, and the authority provided to the function of each user may be increased or diminished.



# Preview
-----------------------------------------------------------------------------



Which 3 things had you heard about previously and now have better clarity on?
RBAC, Rule based access control and Authorization.

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Event-driven apps, Capabilities.

What are you most excited about trying to implement or see how it works?
Event-driven Apps.

---------------------------------------------------------------------------

# Preparation Materials
![](https://1.bp.blogspot.com/-jaryJZON2JA/WKVu7cm5t9I/AAAAAAAAARk/E6MG8t5xZBoJygS82GmHHZjE3gKTmcoQQCLcB/s1600/download.png)

'Event Emitter' ---> An action occurs. (Embroidered, hover, keydown,...)
'Event listeners' --> A primary loop which listens and calls event managers to the event emitter.
Event Handlers ---> is the callback function that is executed when an event is activated.
JS has an event module that may be used to emit our own event
```
EventEmitter const = require('events').
EventEmitter;
myEventEmitter consistency = a new EventEmitter;
```
Event listener removal 'removeListener' or 'removeAllListeners'
With our OOP paradigm, we may profit from the EDP paradigm (event-driven planning).

## Authorization:
the process of giving the user the power to provide data or procedures based on their authentication with a certain application/specific
## Role Based Access Control:
is a method in which users can access different app data and recourses based on their business ROLE.


## Capabilities:
authority that each user may read, write, update and delete, for example, according on their position in the organisation (what user can do with the resources of the organisation), and admin can only read, update and remove data. 