# Classroom Visual Inventory

For this project I created a visual classroom inventory to replace the existing classroom spreadsheet. This application is public facing, intended for campus classroom users looking for more information about their assigned room. This application was programmed using PHP, MySQL, JavaScript, JQuery, HTML, and CSS.

Link to application: http://irt-pw-cp1.irt.csus.edu/rooms/external/classrooms/new/index.php  

This application dynamically pulls information from several MySQL tables, information such as classroom environment information, the technology in the classroom, multiple pictures of the classroom including 360 pictures, and training material for the installed technology.

## Goals and Challenges

The main goal of this project was to create a more visually appealing way for users to view classroom information. After searching to see how other campuses displayed classroom information and drawing up wireframes, we settled on the current design.

We also wanted to simplify the searching process by setting predetermined search options and removing most technical terms.

Another goal of this project was to include more information about the room. This was accomplished by adding more room pictures, adding more training material, and adding room descriptions. The addition of more room pictures included adding 360 degree photos of all of the rooms, these can be seen in the picture slideshow. The training material being displayed is dynamically chosen based on the technology in the classroom. Many of the room descriptions are currently based on room environment and technology in the room, but I also added the ability to add a room specific description.

I also wanted to clean up the MySQL database tables. The classroom spreadsheet was generated from a table that pulled data from three other tables. This table required regular maintenance when new equipment was being used. Instead of maintaining this table, I virtually create part of it in the SQL statement for the webpage and run a different query to access the other information.

## Before

![Before picture](/CVI_4.PNG)

## After

Initial landing page:\
![Application landing page picture](/CVI_1.PNG)

Search results:\
![Search results picture](/CVI_2.PNG)

Clicking into a room:\
![Specific room information picture](/CVI_3.PNG)
