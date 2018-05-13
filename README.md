# Scrum Task Management

[![Version][npm-image]][npm-url]  Scrum Masters can create tasks for employees in this project.

This project powered by React.JS and Express.

![Screenshotv](http://oi63.tinypic.com/29e5fnk.jpg)

Open command line and apply that steps:
-----------
```
1. Step
 git clone https://github.com/mreorhan/Scrum-Task-Management-with-ReactJS-Express-Server/ scrumtaskmanagement

2. Step
 cd scrumtaskmanagement
 npm install
 npm start

3. Step (open new command line)
 cd scrumtaskmanagement/client
 npm install
 npm start

4. Step
 You can start working on which explorer window.
```


HTTP Request
-----------
GET: http://localhost:5000/tasks     --> Show all tasks

POST: http://localhost:5000/tasks    --> Add new task
[headers]:
	{
		title:        string *required*,
		content:      string,
		status:       number *1,2,3,4*,
		dueDate:      Date,
		createdBy:    Object.Id
		contributors: Object.Id
	}

GET: http://localhost:3000/users   --> Show all users
  
  Contributing
------------

See [Contributors](CONTRIBUTORS.md).

[npm-image]: https://img.shields.io/npm/v/react-toastr.svg?style=flat-square
[npm-url]: https://www.npmjs.org/package/react-toastr

![Screenshot](https://lh3.googleusercontent.com/qd0MI1JKjOfd2Z9KDx3ZMsGrHPqma0J5oLfN9cn8XjOJ6EQXCMQVfko67YxvmnMLFZbBge0_m8ENHjpAeOKj=w1920-h917-rw)

