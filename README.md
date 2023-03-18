# StopWatch
For Stopwatch i have created three files: index.html,script.js and style.css.

index.html------
At first i have added the default text and with that default text i have also linked the style.css.
Here in index.html, I have created one outer div and two innre div.
In outer div,I have created id as a container which will contain total stopwatch and also I have taken two heading tags.
First heading tag is of name coding ninjas and second heading tag is of name stopwatch.
In the outer div,First inner div is for time which will contain four class that is hour,min,sec,count(millisec).
Second inner div is for buttons which will contain three class that is start,stop,reset.
At last in index.html , I have linked the file script.js.

script.js-------
I have taken three variables for the stopwatch as start,stop,reset which will get the id of the start button,stop button and reset button.
Now i have assigned the value of hour,min,sec,count.
now i have taken addeventlistener to call the function.If i click start button then it will call the function stopwatch and the timer becomes true( True means start).
By clicking stop button then it will call the function stopwatch and the timer becomes false (false means stop).By clicking reset button then it will call the function stopwatch and the timer becomes false along with hour = 00,minute = 00,second = 00,count = 00.
in 31st line , the function stopwatch becomes start then the timer will add count++ means count begins start.
if the count== 100,then the second will with increase +1 and count becomes 00.
if the second==60,then the minute will with increase +1 and second becomes 00.
if the minute==60,then the hour will with increase +1 and minute becomes 00.
In second function,if hour<10 then hrString will be 01,02,03,......,09.
if minute<10 then minString will be 01,02,03,......,09.
if second<10 then secString will be 01,02,03,......,09.
if count<10 then countString will be 01,02,03,......,09.
after that i have created an inner html.

Style.css-------
in style.css normally it contains the background image,size,margins,colour,etc with pixels and percentage.
background colour,Stopwatch border,Stopwacth size,Buttons colours,fonts,etc. which is given in the code.
