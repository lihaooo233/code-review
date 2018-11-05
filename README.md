# code-review

![draft](https://github.com/lihaooo233/code-review/blob/master/solution-diagram.jpg)

## description:

There are several parts in the diagram which are achieved by different technology. Some of them seems a little beyond my level.
And I will show what I learn from the project of AgileBU project (https://github.com/ayshimz/AgileBU).
## React application:
The front end used create-react-app which is a useful tool of facebook. It is much easier to focus on code because the environment of 
node.js is aleardy configured. That is a smart choice if you want to create a react application. 
## readme:
I have to say the readme of the project is really awesome, especially the backe-end part, I learnt a lot from it about how to use
PostgreSQL database. Very detailed.

## Login system:
The Login system used react-google-login module(https://github.com/anthonyjgrove/react-google-login). User could log in the system
by using their google account, and the call-back information may could help the system identify the user.

## interaction:

![draft](https://github.com/lihaooo233/code-review/blob/master/examp.png)
The achieved functions are log in, move blocks to other lines. The functions work well and the idea is interesting! However, it seems
That users could not create a new blocks or get information from database to create a block. And my advice is that you could try to 
add a function that could edit every information of a block(name,email address...). Besides, I think there should have a empty space 
for each block to let instructers add some notes.The program used react-beautiful-dnd(https://github.com/atlassian/react-beautiful-dnd) to achieve most of the function. Because of a comment of Board.js , I find the tutorial video of how to install and use react-beautiful-dnd. I think this comment should be more obvious( better to be showed in readme ), or it is quite difficult to find. 
The code follows the dragdrop function of react-beautiful-dnd and add one more line(seems the example only has two lines) and add some css style make the whole function more beautiful, this is very good. Store different css and js file seperately is a good manner which I should learn.
And the log in function followed the react-google-login and it works properly
Some advices: 1. I think more comments could let the code easier to understand. 2. I think you could make a sort function (base on the first letter of username maybe) to sort the blocks of each line which could let the page seems  cleaner.
Your assessment of their testing

## backend-database:
Used PostgreSQL to store the data like id, email and name, Conveniently enough.

## documents:

https://github.com/atlassian/react-beautiful-dnd

https://reactjs.org/

https://github.com/anthonyjgrove/react-google-login

https://www.postgresql.org/
