# Next 

https://drive.google.com/file/d/1gU9d2Y3oZch_Z6wRPOYxOG0cTlt6uA0c/view?usp=drivesdk





https://drive.google.com/file/d/1gU9d2Y3oZch_Z6wRPOYxOG0cTlt6uA0c/view?usp=drivesdk

https://drive.google.com/drive/folders/1ozpdbShpwA4rxaTcxqQZnwWDT6rYHY2O
AJAX – Real Time Examples

• Here is a list of some famous web applications that make use of AJAX.

1. Google Maps
• A user can drag an entire map by using the mouse, rather than clicking on a
button.

2. Google Suggest
• As you type, Google offers suggestions. Use the arrow keys to navigate the
results.

3. Gmail
• Gmail is a webmail built on the idea that emails can be more intuitive, efficient,
and useful.

4. Yahoo Maps (new)
https://cgccollegespace.live

• Now it's even easier and more fun to get where you're going!

How AJAX works?
AJAX communicates with the server using XMLHttpRequest object. Let's try
to understand the flow of ajax or how ajax works by the image displayed
below.

As you can see in the above example, XMLHttpRequest object plays an
important role.
1. User sends a request from the UI and a javascript call goes to
XMLHttpRequest object.
2. HTTP Request is sent to the server by XMLHttpRequest object.
3. Server interacts with the database using JSP, PHP, Servlet, ASP.net
etc.
4. Data is retrieved.
5. Server sends XML data or JSON data to the XMLHttpRequest callback
function.
https://cgccollegespace.live

6. HTML and CSS data is displayed on the browser.

Understanding XMLHttpRequest
1. XMLHttpRequest
2. Properties of XMLHttpRequest
3. Methods of XMLHttpRequest
An object of XMLHttpRequest is used for asynchronous communication
between client and server.
It performs following operations:
1. Sends data from the client in the background
2. Receives the data from the server
3. Updates the webpage without reloading it.

Properties of XMLHttpRequest object
The common properties of XMLHttpRequest object are as follows:

https://cgccollegespace.live
Property Description
onReadyStat
eChange

It is called whenever readystate attribute changes. It must
not be used with synchronous requests.

Methods of XMLHttpRequest object
The important methods of XMLHttpRequest object are as follows:

https://cgccollegespace.live
readyState represents the state of the request. It ranges from 0 to 4.

0 UNOPENED open() is not called.
1 OPENED open is called but send() is not called.
2 HEADERS_RECEIVED send() is called, and headers and
status are available.
3 LOADING Downloading data; responseText holds the
data.
4 DONE The operation is completed fully.

reponseText returns response as text.
responseXML returns response as XML

Method Description
void open(method, URL) opens the request specifying get or

post method and url.
void open(method, URL, async) same as above but specifies
asynchronous or not.

void open(method, URL, async,
username, password)

same as above but specifies
username and password.
void send() sends get request.

Advantages of AJAX:
1. Reduces the server traffic and increases the speed

2. Ajax is responsive and time taken is also less

3. Form validation

4. Bandwidth usage can be reduced

5. Asynchronous calls can be made this reduces the time for data arrival.

Disadvantages of AJAX:
1. Open-source

2. Active x request is created only in internet explorer and newly created web browser

3. For security reasons, you can only access information from the web host that serves
pages. Fetching information from other servers is not possible with Ajax.

What is JSON
JSON is an open standard for exchanging data on the web. It supports data
structures like object and array. So it is easy to write and read data from
JSON.JSON stands for JavaScript Object Notation.
● JSON is an open standard data-interchange format.
https://cgccollegespace.live
void send(string) send post request.
setRequestHeader(header,value) it adds request headers.

● JSON is lightweight and self describing.
● JSON originated from JavaScript.
● JSON is easy to read and write.
● JSON is language independent.
● JSON supports data structures such as arrays and objects.

Features of JSON

1. Simplicity
2. Openness
3. Self Describing
4. Internationalization
5. Extensibility
6. Interoperability

JSON Example
In this tutorial, you will get a lot of JSON examples to understand the topic
well. The JSON file must be save with .json extension. Let's see a simple
JSON example.
File: first.json

1. {"employees":[
2. {"name":"Sonoo", "email":"sonoojaiswal1987@gmail.com"},
https://cgccollegespace.live

3. {"name":"Rahul", "email":"rahul32@gmail.com"},
4. {"name":"John", "email":"john32bob@gmail.com"}
5. ]}

JSON vs XML

A list of differences between JSON and XML are given below.

https://cgccollegespace.live
No. JSON XML

1) JSON stands for JavaScript
Object Notation.

XML stands for eXtensible Markup
Language.

2) JSON is simple to read and
write.

XML is less simple than JSON.

3) JSON is easy to learn. XML is less easy than JSON.

4) JSON is data-oriented. XML is document-oriented.

5) JSON doesn't provide
display capabilities.

XML provides the capability to display
data because it is a markup
language.

6) JSON supports arrays. XML doesn't support arrays.

JSON Example
1. {"employees":[
2. {"name":"Vimal", "email":"vjaiswal1987@gmail.com"},
3. {"name":"Rahul", "email":"rahul12@gmail.com"},
4. {"name":"Jai", "email":"jai87@gmail.com"}
5. ]}

XML Example
1. <employees>
2. <employee>
3. <name>Vimal</name>
4. <email>vjaiswal1987@gmail.com</email>
5. </employee>
https://cgccollegespace.live
7) JSON is less secure than
XML.

XML is more secure.

8) JSON files are more human
readable than XML.

XML files are less human readable.

9) JSON supports only text
and number data types.

XML supports many data types such
as text, number, images, charts,
graphs etc. Moreover, XML offers
options for transferring the format or
structure of the data with actual data.

6. <employee>
7. <name>Rahul</name>
8. <email>rahul12@gmail.com</email>
9. </employee>
10. <employee>
11. <name>Jai</name>
12. <email>jai87@gmail.com</email>
13. </employee>
14. </employees>

Similarities between JSON and XML

● Both are simple and open.
● Both support unicode. So internationalization is supported by JSON and
XML both.
● Both represent self describing data.
● Both are interoperable or language-independent.

JSON Data Types

Valid Data Types

In JSON, values must be one of the following data types:

https://cgccollegespace.live

● a string
● a number
● an object (JSON object)
● an array
● a boolean
● null

JSON values cannot be one of the following data types:

● a function
● a date
● undefined

JSON Strings

Strings in JSON must be written in double quotes.

Example

{ "name":"John" }

JSON Numbers

https://cgccollegespace.live

Numbers in JSON must be an integer or a floating point.

Example

{ "age":30 }

JSON Objects

Values in JSON can be objects.

Example

{

"employee":{ "name":"John", "age":30, "city":"New York" }

}

Objects as values in JSON must follow the same rules as JSON objects.

JSON Arrays

Values in JSON can be arrays.

https://cgccollegespace.live

Example

{

"employees":[ "John", "Anna", "Peter" ]

}

JSON Booleans

Values in JSON can be true/false.

Example

{ "sale":true }

JSON null

Values in JSON can be null.

Example

{ "middlename":null }

https://cgccollegespace.live

JSON Object

JSON object holds key/value pair. Each key is represented as a string in
JSON and value can be of any type. The keys and values are separated by
colon. Each key/value pair is separated by comma.
The curly brace { represents a JSON object.
Let's see an example of JSON object.
1. {
2. "employee": {
3. "name": "sonoo",
4. "salary": 56000,
5. "married": true
6. }
7. }
In the above example, employee is an object in which "name", "salary" and
"married" are the key. In this example, there are string, number and boolean
value for the keys.

JSON Object with Strings
The string value must be enclosed within double quote.
1. {
2. "name": "sonoo",
https://cgccollegespace.live

3. "email": "sonoojaiswal1987@gmail.com"
4. }

JSON Object with Numbers
JSON supports numbers in double precision floating-point format. The
number can be digits (0-9), fractions (.33, .532 etc) and exponents (e, e+,
e-,E, E+, E-).
1. {
2. "integer": 34,
3. "fraction": .2145,
4. "exponent": 6.61789e+0
5. }

JSON Object with Booleans
JSON also supports boolean values true or false.
1. {
2. "first": true,
3. "second": false
4. }

JSON Nested Object Example
A JSON object can have another object also. Let's see a simple example of
JSON object having another object.
1. {
2. "firstName": "Sonoo",
3. "lastName": "Jaiswal",
4. "age": 27,
5. "address" : {
https://cgccollegespace.live

6. "streetAddress": "Plot-6, Mohan Nagar",
7. "city": "Ghaziabad",
8. "state": "UP",
9. "postalCode": "201007"
10. }
11. }

JSON Array

JSON array represents an ordered list of values. JSON array can store
multiple values. It can store string, number, boolean or object in JSON array.
In JSON arrays, values must be separated by comma.

The [ (square bracket) represents JSON array.

JSON Array of Strings
Let's see an example of JSON arrays storing string values.

1. ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday",
"Saturday"]

JSON Array of Numbers
Let's see an example of JSON arrays storing number values.
1. [12, 34, 56, 43, 95]

JSON Array of Booleans
Let's see an example of JSON arrays storing boolean values.
https://cgccollegespace.live

1. [true, true, false, false, true]

JSON Array of Objects
Let's see a simple JSON array example having 4 objects.
1. {"employees":[
2. {"name":"Ram", "email":"ram@gmail.com", "age":23},
3. {"name":"Shyam", "email":"shyam23@gmail.com", "age":28},
4. {"name":"John", "email":"john@gmail.com", "age":33},
5. {"name":"Bob", "email":"bob32@gmail.com", "age":41}
6. ]}

JSON Multidimensional Array
We can store array inside JSON array, it is known as array of arrays or
multidimensional array.
1. [
2. [ "a", "b", "c" ],
3. [ "m", "n", "o" ],
4. [ "x", "y", "z" ]
5. ]

AJAX JSON Example

We can get JSON data by AJAX code. AJAX provides a facility to get
responses asynchronously. It doesn't reload the page and saves bandwidth.
https://cgccollegespace.live

AJAX JSON Example
Let's see a simple example of getting JSON data using AJAX code.

1. <html>
2. <head>
3. <meta content="text/html; charset=utf-8">
4. <title>AJAX JSON by Javatpoint</title>
5. <script type="application/javascript">
6. function load()
7. {
8. var url = "http://date.jsontest.com/";//use any url that have json
data
9. var request;
10.
11. if(window.XMLHttpRequest){
12. request=new XMLHttpRequest();//for Chrome, mozilla etc
13. }
14. else if(window.ActiveXObject){
15. request=new ActiveXObject("Microsoft.XMLHTTP");//for IE only
16. }
17. request.onreadystatechange = function(){
18. if (request.readyState == 4 )
19. {
20. var jsonObj =
JSON.parse(request.responseText);//JSON.parse() returns JSON object
21. document.getElementById("date").innerHTML =
jsonObj.date;
22. document.getElementById("time").innerHTML = jsonObj.time;
23. }
24. }
https://cgccollegespace.live

25. request.open("GET", url, true);
26. request.send();
27. }
28. </script>
29. </head>
30. <body>
31.
32. Date: <span id="date"></span><br/>
33. Time: <span id="time"></span><br/>
34.
35. <button type="button" onclick="load()">Load
Information</button>
36. </body>
37. </html>
Output:

Date:

Time:

UNIT -6 COMPLETED

https://cgccollegespace.live
Load Information
