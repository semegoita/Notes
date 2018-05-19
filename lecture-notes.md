Notes

* what is id and classes.
In CSS Every element I s a box.
difference between margin and padding.
Padding is the space between the content and the border
Margin is the space between boxes.

Many elements are rendered as blocks by a browser.
Block elements:
Inline elements: word wraps

Refactor: making something better and cleaner.

Fot clearing after float
.selector {
clear: both;

.clearfis:: after {
content: “”’;
display block;
clear:
}

positioning
default positioning is static.
Absolute: relative to the entire page/website.
Or relative to its parent element./if positioned absolute.
Relative. Starting from the existing position.

Z-index. Postionning like the third dimentions on top of  one another.
By default it is 0.

Escaping is giving –ve value. Is out of the visible area.

Refer about:

Google developer tools.




Libraries

Are set of codes written by other people to be used by you.

Css resets (is a library) help us write cross browser codes.

Semerehg.github.io publish it like this.

Line length= usually 50-75

Sans-serif vs serif – font type more common the firsrt one

Pseudo classes: are selectors that help us select certain aspects like
: hover;
: link;
focus
: last-of-type;

button with various states
default
hover
focus
active

Bootstrap.
Wireframe: is the most important step in designing a product.
It is a sketch of your product.
Wireframe tools to be referred.
Designing with a grid in mind.

Bootstrap see everything as row and columns.
Every bootstrap grid is made up of
•    Container
•    Rows
•    Columns
Lg,md,xs,sm are the treshholds that specify. The size of our screen.
•
Mark-up is the picture look like of the website to look like.

Donot add content to a row always put them in columns

Humberger tabs gets created automatically by bootstrap.
•    Panel gives something like borders.
We can create rows inside columns.
Always start with creating rows and then columns.
Media queries
•    this gives rules to bootstrap
•    if the browser is between this width use this css.
Eg. @media screen ……………
@ media print make it better looking for printing.
Usually media queries are written at the end of your code to overwrite what is written.
Do activity 17 in sec 2.

Formatting languages(html and css)


Java Script
Basic variables:
Variable: labeled container for data.
Variable has a name and a value.
•    Equal sign is assignment in variables not equal it puts staff in a container(variable).
To organize data entered from users has to be organized like names, and staff.

Java script is case sensitive.
Use variables names in camel case style.

Syntax for variables in java script

Console.log(“teacher”); important for debagging.
Console.log(variablename);

Resolve: means it uses assignment from the variable and use it for computation.
First thing to do while dealing with java script is insert conslole.log.
You can insert console.log every few line of code.
•    Alert
•    Prompt
•    Confirm
document.write(); spits js codes on the screen.

If (condition) {
•    Give a value here if condition is met
}
else {
•    give value you want to be displayed.
}

double equal tries to convert file types so not consistent. Advised not to use it.

functions
   1 input
   2 output
   3 sideeffects
   
   persistence data that persists
   
client side storage.
   1 cookies
   2 local storage

server side storage
    server-side is basically the same as backend
    Databases are server side.
    conbined each web app/compandy has unified storage
   
there are 3 different types os client side storeage
    1 local storage
    2 session storage
            exactly the same as local storage, but is auto deleted after a little bit of time
    3 cookies
            - archaic, used today only ofr certain tracking things


there is a local storage for every website and different websites can access each others local strorage.
the local storage has three pertinent methods
        1 clear();
        2 set();
        3 get();

call back functions are funcions that are passed as arguments to be called back latter.

to access data inside a funcjion out of scope we can use return or the better way to use call back.

DEFINITIONS

- Schema - shape of data
  - More specifically:
    - The shape of data in a database
    - That is, what are our tables, columns, and types
    - The structure, not the content
    - Columns and tables only
    - Names of columns, data types
-SEED 
        data to feed schema.
- Migration
  - Code that modifies schemas of existing databases
  - Way to create tables, add rows, delete rows, etc

DATA BUZZWORDS
        Small data
                put everything into a file
                put everything in to a variable
                arrays, ovjects, etc anydata type in node 
                1000s
        Medium data
                100000s
                too big to be easinly used in a single file 
                more than one person might be using this 
                use databases
        Big data
                Too big for a single computer to use 
        Index
            property of a column
            some columns 
            
    Query speeds tips
    * If you are runnning it like a report then speed generally doesniot matter
    * IF you are running it on every request, then speeds Deoes matter.
                
MVC is a programming paradigm, an "organizationl system" for code

- Model
  * Purpose: Store and retrieve data in a clean and dependable way
  * Gatekeeper to persistence in the database
  * Code that does all database work
- View
  * Purpose: Displaying information to client
  * HTML / CSS / Frontend JavaScript
  * Often templated using a templating language
- Controller
  * Purpose: "Business logic", make decisions on how the application should function
  * All the "moving parts" of the app
  * We use express for this

OOP - Object Oriented Programming
- Multi page app
  - Doesn't necessarily need front-end JavaScript
  - Has "real links" - e.g. <a href="/other/page">click</a>
  - Each page is generated typically with templating
    languages on the backend with the data pre-inserted
  - Backend-heavy: Logic of assembling HTML takes place on the
    backend

- Single page app
  - Sends single HTML file that contains javascript code
  - Don't have "real links", just buttons that trigger
    front-end JavaScript code
  - This JavaScript code uses GET and POST requests (AJAX)
    and DOM manipulation to make the interactive website
  - It queries GET and POST routes on the server that return
    JSON data from the DB
  - Frontend-heavy: Logic of assembling HTML takes place on
    the frontend