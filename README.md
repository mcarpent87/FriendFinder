# FriendFinder

Live Link:
https://dashboard.heroku.com/apps/protected-shelf-15607

Instructions:
Answer a quick survey and you will be matched with a friend that is most compatiable to your answers. It's that easy! You can also access the
API to view users information. 

Files that make this app run:
server.js file intializes the express server on the port number specified in the file. 
Two routing files (htmlRoutes.js and apiRoutes.js) handle the logic on the back end based on the request made by the user.
friends.js holds user data in an array. As uers take the survey, thier information and answers are added to this file as a JSON object that can be viewed in the API. 
2 HTML files (home.html and survey.html) make up the front end portion of the app, these are the two pages that the server routes the user to.
A modal imbedded within the survey.html file pops up when the survey is submitted. It pulls up the calculated best match for the user based on the answers on thier survey.
Multiple npm install packages are necessary for this app to run properly. 

Technologies Used:
JavaScript
jQuery
node.js
Express.js
HTML 5
Bootstrap 4
CSS 3
