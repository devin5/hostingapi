Deployment Notes
Web Servers run web applications

accept requests from clients
send back responses to clients
Web servers are a software running on someone's machine

[client] === [web server (multiple web applications/apis)]

Dev process

write code
commit and push
profit (it's deployed automatically to heroku)
Steps to prepare our API for deployment to Heroku

make the port dynamic
setup a "start" script that uses node (not nodemon) to run our server
The environment is the platform (the place/operating system/machine) where the application is running.
