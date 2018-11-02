# code-review

![draft](https://github.com/lihaooo233/code-review/blob/master/solution-diagram.jpg)

#description:

There are several parts in the diagram which are achieved by different technology. Some of them seems a little beyond my level.
And I will show what I learn from the project of AgileBU project (https://github.com/ayshimz/AgileBU).

# Login system:
The Login system used react-google-login module(https://github.com/anthonyjgrove/react-google-login). User could log in the system
by using their google account, and the call-back information may could help the system identify the user.

# interaction:
The achieved functions are log in, move blocks to other lines. The functions work well and the idea is interesting! However, it seems
That users could not create a new blocks or get information from database to create a block. And my advice is that you could try to 
add a function that could edit every information of a block(name,email address...). Besides, I think there should have a empty space 
for each block to let instructers add some notes.

# backend-database:
Used PostgreSQL to store the data like id, email and name, Conveniently enough.
