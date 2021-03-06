
:pushpin: Todo Challenge :pushpin:
=================

This project is the week 7 challenge from Makers Academy. The task was to build a Todo list as a mini front-end application with Javascript, AngularJS and Karma and Protractor for testing. A database didn't have to be used as the front-end is more important.

Heroku
----
[Guillaume's Todo challenge](link_to_come)

![](public/images/main_screen_screenshot.png)

![](public/images/tasks_screenshot.png)

Technologies used
----
- Javascript
- AngularJS
- Node Server
- Npm & Bower
- Karma and Protractor
- Selenium Server & WebDriver
- grunt & jshint
- jQuery

How to run it
----
```
git clone git@github.com:GBouffard/todo_challenge.git
cd todo_challenge
npm install
bower install
npm start
```
By opening your browser on http://localhost:3000/, you can now add new tasks, tick them, delete them and play wit the tasks manager.

How to run tests
----
```
cd todo_challenge
npm test
```
This is what you should see
![](public/images/Karma_screenshot.png)

In 3 different terminals:
```
webdriver-manager start
http-server
protractor test/e2e/conf.js
```
And this is what you should see
![](public/images/Protractor_screenshot.png)