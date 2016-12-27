#Simple Derby App

Derby.js is a reactive full-stack Javascript framework for creating modern web applications without the need to write
complicated code.
With Derby you can easily build real-time applications that will run simultaneously in the Node.js server and the browser.

##Environment Requirements

```
Node.js (>=0.10)
MongoDB
Redis (>=2.6) is optional (used to scale past one server process).
```

##Quick Start

Now install the dependencies and start running the server

```bash
$ git clone https://github.com/shilpadhagat/derbyApp
$ cd derbyApp
$ npm install -g coffee-script
$ cd derbyApp/frameworks
$ coffee server.coffee
```

If everything goes well you should see this

```bash
> Master pid  #####
> ##### listening. Go to: http://localhost:8007/
```

Now your app is running at [http://0.0.0.0:8007](http://0.0.0.0:8007)

For more information go to  http://derbyjs.com/.
