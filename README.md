# -Change-Bootstrap-Theme-of-Website-with-PHP-and-MySQL-32-views3-days-ago
Hello YouTube , I'm Moiz Iqbal    &amp; Today I'll Tell You how to change your website themes bassed on Bootstrap via PHP &amp; MySQLi It's Very Simple Coding if you have some basic concepts of PHP And MySQL  Just Follow The Steps :  1. Create your database.  2. Create table 'themes' inside your database.  3. Make the fields (id,name,min,css,status)   4. Now visit www.bootswatch.com for bootstrap themes.  5. Now insert some records in your database table via phpmyadmin. just Follow Me  6. Open Your Favorite text edit for php script. im using sublime text 3  7. Make a connection file. Include it in your index.php file and  8. Make a layout that you want.   9. Make a form for input the theme name from user Via Dropdown,Text Field or Radio Option etc.  10. Im making a select tag. inside select tag i'll select all the theme name stored in database table and make some option dynamic via while loop. Be Sure 'option' tag should take value of 'id' field.  11. Get the value and hit submit button via post method. When the value is taken so we have to update the status of table field to '1' that will represent that theme is active. But it should we update '1' status to that record taht is requested other should be remains zero '0'  Dont Worry it's Very Easy.  12. When the record is update then fetch the record that has status '1' and via mysqli_fetch_assoc() function.  13. Now get the 'min' and 'css' fields data and echo those out inside the style tag  14. Thats it :)  15 If you like this please subscribe for more videos :)
