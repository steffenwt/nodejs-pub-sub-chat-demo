<h1>Chat based on Node.js using Redis Pub/Sub + socket.io</h1>
Simple application based to show Redis Pub/Sub mechanism together with Node.js and socket.io.

<h1>How to get the application running</h1>
<ul>
<li><a href="http://redis.io">Redis</a> must be installed and running.
<li><a href="http://nodejs.org">Node.js</a> must be installed
<li>npm install
<li>npm run redis OR npm run sockets
</ul>

Start via:

$ node app_redis.js

Fire up your favorite browser and go to "localhost". Open more browser windows to see it in work.

Hint:
A non-redis version just based on socket.io can be started with:

$ node app.js

<h1>Credits</h1>
This example is based on a Cramp application originally written by <a href="https://gist.github.com/348262">Pieter Noordhuis</a> and also based on <a href="https://github.com/lifo/cramp-pub-sub-chat-demo">cramp-pub-sub-chat-demo</a>.