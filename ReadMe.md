## Class 01 - React

### Overview  
  
<p>The React.js framework is an open-source JavaScript framework and library developed by Facebook. Reactjs is the most popular of programming lnguages at the moment. It's called React because it reacts to changes and updates the state. It's a library that only renders the view for UI.</p>  

React builds user interfaces and applications quickly and efficiently using less code than you would with JavaScript.  
  
In React, you develop your applications by creating reusable components that you can think of as independent building blocks, like using Lego! These components are individual pieces of a final interface, which, when assembled, create the whole user interface. There is a virtual DOM and the real DOM which React updates  
  
Twitter is an example of creating seperate componets for a whole UI interface.  
  
This is a informative YouTube video https://www.youtube.com/watch?v=N3AkSS5hXMA  

### My notes   
  
React uses component based architecture - there are different types of architecture: header, footer, side and these are components.  
There will be other components depending on what you are building  

For every component there are 4 characteristics, these are:  
  
1. Imports  
2. Styles - this is CSS  
3. Functions - this is js  
4. Exports  
  
Component based architecutre has points that make is good to use:

1. consistency  
2. efficiency  
3. data - only working with data in a single component at a time  
4. easy to debug (see 3. above)  
5. reusable - write is once, use again  
6. replaceable - do not need to change the whole page, just the comonent  
7. maintainable  
8. reliable  
9. independent - if there is a problem only one component is affected 

### Class 1 (Tim)  

Props - short for properties, passes info from one component to another BUT can only pass value down the hierarchy (bubble up - if run a fuction as a prop somehow takes the property upwards? not sure about this)   

Props is when you parse a component giving info from one component to another    
prop is e.g. 
``
functionHeader ({handleMode})
``

Destructuring   

const - cannot change, if you use const and try to change it will error 

let - can change 

dot notation .return 
get me this item from this location e.g. tim.location 

jsk - mix of js and html  

ASCII  
Why is ASCII used?
ASCII is used as a method to give all computers the same language, allowing them to share documents and files. ASCII is important because the development gave computers a common language.  It has largely been replaced by UNICODE  

### Class 2 (Tim)  
##### React State  

in app js in function app(){}  
can do any js you like  

#### Default  
when you import something from something it assumes its default eg App in the App component - but use curly brackets to make it look for the name (destructures it)  

For below we did the Paul O'Grady exercise to pat his head  

++ increases by one  
take a value, change it and it re-renders on the page 
``
const [Pats, setPats] = useState(0):
``   
here Pats is the state variable, setPats is the mutation function, useState returns your array and destructures output of setPat, (0) is the inital value   

JSON  

Array  

regular function  

for Each   

anonymous function - function()  

function needs brackets   

{} is an object   

map() accepts 1 parameter - its an argument, needs to be a function   

arrow function ==> is just a function   

1 rem is 16px  

vw - viewport width    
vh - viewport height  

### Modals   

&& is ##### and - unless all is true doesn't run
|| is ##### or (computer only has to check until true no matter how many, it stops looking  

code in brackets () is executed first 

==
=== always use triple equals   
1===1  
"1"==="1" - or use 2 equals means true (i don't get this)   
1=="1" will look to see if the frist number 1 is a string and make it a string, if use === triple equals won't convert to a string    

$ string literals 

An exclamation mark is called a "bang"   

!show modal - this sets it to the opposite of what it currently is  so ! means not and !false means true (so it's not false so means it's true)   

parse from App {handleModal} to Main and from Main to horned Beast 

In horned Beasts make beasts a modal  
modalData will be an object because the data is already an object  

state variables you can change but not the type   

in JSON data is modal object as one of the beasts   

Parameter in function    

``
function greet (name)   
greet("Tim")   
``   
(name) is the parameter   
("Tim") is the argument 

modalData is beast    

In modal js  

brackets after function is what invokes the function  

see Discord 12/04 post    

& is a gate - an abbreviation of 'if'   

### Forms 14/04   
``
data.map(function(){   
``   
map is a function   

fieldset - border round form in the form element   
html for - so you can click on cake label on form  

in forms text is default so don't need to tell it text   

function onChange used because it's like onClick - click and run a function   

``
setForm({...form, Event.target.name:event.target.value}``  this is js due to curly bracket   

...spread - tells the computer to give the item in the object (properties/innards) without the curly bracket - see line 16    

### Class 6 APIs   

order of execution   WRRC - web request response cycle 

client - is what you're coding, the website when communicating with multiple things e.g. server -> database   

http - hyper text transfer protocol (its a verb)    

##### CRUD
- Create  
- Read  
- Update  
- Delete  

asynchorous code  - you can't guarentee how long it will take to execute  

asynch - code happening seperately   

if you call an api in the url - apis are just urls that returns lots of data   

axios - node module.  It's a third party call when you use axios   
the function runs axios get don't know how long this will take - get a promise so have to use await so it happens rather than just a promise.  To use await (js) need to use asymch before the function - you have to use asynch and await - that's just what you have to do <shrugs>   

res - is response  

App component is one that holds it all together and will hold all the components  

##### Three things about React:    
- passing props   
- using state  
- passing functions 

modal uses state and props 

modal not React but uses stae and props to make one 

### Class 7  Express  20/04   

Express is a library of functions to make a library of stuff  

building your own server  

``npm i express`` is to create a server 

dotenv cors nodemon - you leave a space between them so computer will install them all  

dependencies - we need functions which are in the node - we are dependant on them, we can put them in ourselves but why would we?  this is like takeaway food - the nodes are ready to go 

JSON is an object but all in strings, key value pairs  

API as another website can grab the data.  API - a website address that returns data  

use 'require' rather than import (see demo code)  

using dot notation to configure objects  

##### PORT 8080
every website is on a port, when running npm start its where to host e.g. Plymouth has 15 ports - your ship lives in port 8080  

have to use localhost:8080.  In React you use 3000  

express is a function that returns an object - when a variable runs an object  

CORS -  middleware, a bridge between the CLIENT and the SERVER   

DEMO:   
line 1-23 will be the same forever for Express - its the default   

line 19 app.get is the R in CRUD  

line 20 get takes 2 parameters - the home (or the root) and the callback function  

root is the home   
route is all the different endpoints you can have   

line 16-35 are the objects (the retro games)  

arrays have methods - array.find  

response is an object with methods  

L45 - 53 with 2 routes  

require dotenv configuration as this sets the environment for variables  

const app = express - function   

Line 66 app.listen means listen to this PORT   

Line 46 is the route or root? ("/")  

get is a http method - part of CRUD 
post is create  
get is read  
delete is delete   

*see screen shot from a previous class to get the rest of this and how relates to CRUD* 

every time you refresh a page you are using line 46-48 function  

8080 when visit this using get method  

APIs use URLs to parse (pass) info using URLs  

response.JSON  - i am going to send you JSON data   

Like return in a function is the last thing to run, this is same for response - (so nothing else will happen afterwards)  

line 38 - 42  is vanilla js  

different endpoints bring different data  

Request Query   - ? is start of query   

key value pair 
using '&' between every query   

Request params  - instead of request.query use this  
add a param in endpoint  

only better to use request.query as can use more than one   

params and query are in Class 8 and Class 10   this opens up what you can do 



 



