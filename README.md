# streamTwitter
Sample Project that uses Twitter streaming API and NodeJS

I created a NodeJS sample project using the Twitter public APIs. This application will get all the streaming tweets originating from Vancouver with the keyword "bubblegum" and store it in a MongoDB.
I created this project using Webstorm 10.0.4 with evaluation license.
I selected the NodeJS Express App in creating this project so there is a lot of node modules. I specifically installed and used Twitter and MongoDB for this project by using npm.
The files that I updated and created are bin/www and clientConfig.js.
You have to edit the MongoDB URL in bin/www file to save it to your own database. clientConfig.js should also be updated on your Twitter account's generated token.

Development Environment:
- OS:Windows 7 Professional 32-bit Service Pack 1
- IDE:Webstorm 10.0.4
- DB:MongoDB 3.0.6 32-bit

Known Bugs:
-- Tweets from mobile will not be catched by this application(problem with Twitter's streaming API??)

Technologies Learned:
NodeJS, MongoDB, JavaScript
