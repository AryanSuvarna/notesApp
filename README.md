# Notes App

This is a notes app I created following DCode's tutorial [link to video](https://www.youtube.com/watch?v=01YKQmia2Jw). I have created this project as a means to learn and understand the flow of the JavaScript language.
I am treating this project as a stepping stone to create my own JS projects in the near future.

## Functionality

The notes application performs all the CRUD (Creating, Reading, Updating, Deleting) operations. Additionally, when the files get updated the most recently changed notes are sent to the top of the list of notes. In creating this project, I also got exposure to the localStorage object which is a part of the web storage API. By utilizing this object, it means that all data/notes created has no expiration data. The data will not be deleted even when the browser is closed, and it is available for all future sessions! One disadvantage I discovered about localStorage is that it is limited to 5 MB across all major browsers. This means adding a funcitonality for adding images would not be ideal.

## How it looks
![](/images/homepage.png)
### When you double click a note, it gives an option to delete the note.
![](/images/deleteNote.png)

## Things I have learned from this project

I learned a lot about the syntax and how files interact with one another in JavaScript. I also learned how JavaScript can access and change all of the elements of an HTML page via using HTML DOM methods and properties. Last but not least, I also got a better understanding of how localStorage works and learned about its uses and limitations.