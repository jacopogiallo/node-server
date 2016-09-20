# node-server
A simple, easy-to-install nodejs server for serving static pages.

#### Prerequisites
To effectively run the server, [nodejs](https://nodejs.org/en/) must be installed on the target host.

#### Installing and running _node-server_
After cloning the _node-server_ git repository in a local folder, open a terminal and change the working directory to such folder. 
Then, simply type `npm install` to install all the required dependencies, and `node server.js` to start the server.

#### Serving pages with _node-server_
Once activated, _node-server_ starts serving all HTML pages inside the `public` directory (such as the [hello](https://raw.githubusercontent.com/jacopogiallo/node-server/master/public/hello.html) provided as example). 
To connect a served page, say `hello.html`, simply type `http://localhost/hello.html` in a web browser.
