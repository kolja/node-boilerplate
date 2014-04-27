## Startingpoint for new node.js projects
This project contains some boilerplate code to get a new node.js project off the ground.

Just clone it to a new directory like so:
```
git clone https://github.com/kolja/node-boilerplate <my-new-project>
```
To install the dependencies, you run
```
cd <my-new-project>
npm install
bower install
```
This will create `node_modules` and `bower_components` directories for you.

Afterwards, build the resources (read: compile and concatenate javascript) with the default grunt task:
```
grunt
```
And start the server
```
grunt start
```
This will also start a watch-task that will automatically rebuild resources or restart the server as soon when you start to make changes.

That's it! Your new project is running at [http://localhost:3000/](http://localhost:3000/)

I am changing this repo all the time to adjust it to my needs. I suggest, you fork it and do the same.
