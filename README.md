# nodejs-notes-app

This is my first nodejs app.
It is used to add, remove and list all/specfic notes through command lines.

It is all basic stuff and this app covers:
  1. Node Core Module (File System)
  2. NPM Packages (yargs, chalk, validator)
  
Add a Note Command:           `node notes-app/app.js add --title="First Note" --body="This is my first note";`
Remove Note Command:          `node notes-app/app.js remove --title="First Note";`
List Notes Command:           `node notes-app/app.js list;`
Show a specific Note Command: `node notes-app/app.js read --title="First Note";`

The tutorial followed for this is: The Complete Node.js Developer Course (3rd Edition) by Andrew Mead, Rob Percival (https://www.udemy.com/course/the-complete-nodejs-developer-course-2)
