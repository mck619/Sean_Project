# Sean_Project
  Sean's project to help me learn js
  
## General knowledge
1. read about the dom
2. read about lambdas/anonymous functions, which is a huge thing in JS
3. make sure you sort of understand the devtools console in your browser, and that you can fuck with JS completely in it
4. do hello world in jquery, at least

## d3 stuff
https://www.dashingd3js.com/table-of-contents
http://alignedleft.com/tutorials/d3
https://github.com/mbostock/d3/wiki/Tutorials

## Exercises 

1. make a table in html, using table, tr, th, td, of the chargers roster with columns for name, number, position and draft #
2. using css, color code the rows where blue is defensive and red is offensive
3. move the css into an external css file
4. make a sql table containing the data, query for it on the page, and display it in html
5. using jquery, make it so that when you click on a <td> element, it console.log()s the value of that cell
6. add a new page, so instead of just having chargers.html, you'll also have chargers.php which returns a json string representing the same data contained in the table from chargers.html also from the db
    for 6, you'll want to look at things like https://stackoverflow.com/questions/477816/what-is-the-correct-json-content-type
    http headers for content-type, MIME types, 'application/json', 'text/html'
7. using https://api.jquery.com/jquery.ajax/ , write an ajax call which hits chargers.php and console.log()s the result
8. in html, add a column to the table which changes the CSS background-color of the row from blue/red to black, when they inevitably commit suicide
9. add a button outside of the table, which using https://api.jquery.com/jquery.each/ , turns the css background-color of each row black, just in case the team bus ever crashes
10. add two more buttons outside of the table, one of which removes all of the inner-text from each <td> element, and the other uses the data obtained from 7 to repopulate the table

put those instructs in your read.me or whatevre github's weird format is and label each commit with the number when you're done with each step and push at least every time you complete one of them
