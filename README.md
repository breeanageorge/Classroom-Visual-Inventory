# Classroom-Visual-Inventory

For this project I created a visual classroom inventory to replace the existing classroom spreadsheet. This application is public facing, intended for campus classroom users looking for more information about their assigned room.

Link to application: http://irt-pw-cp1.irt.csus.edu/rooms/external/classrooms/new/index.php

## Before

This is what the classroom spreadsheet 

![picture](/CVI_5.PNG)

## Databases

One of the goals of this project was to clean up the MySQL database tables. The classroom spreadsheet was generated from a table that pulled data from three other tables. This table required regular maintainence when new equipment was being used. Instead of maintaining this table, I virutally create part of it in the SQL statement for the webpage and run a different query to access the other information.
