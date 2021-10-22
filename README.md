# football-stats-api
<strong>RESTful API in Node with Express.js</strong>
<br>
This repository follows along Andrew Bliss' tutorial at RapdiAPI Blog.

Two fixes in the tutorial are credited to https://github.com/rushuifang/create-your-own-api

1.  In /index.js line 16, while using express middleware one should specifiy the required module's name instead of the module's path.

2.  In /routes/stats.js, the tutorial didn't define statsFilePath in POST, UPDATE and DELETE methods.

MY NOTES:<br>
npm init<br>
npm install express body-parser morgan<br>
npm i nodemon

We need to install body-parser and morgan so that Express can accept JSON and provide logging.

Each record will contain:
- an id of the Football player
- wins
- losses
- points scored

Create a folder called routes<br>
Create a file called stats.json<br>
Create a file called stats.js
