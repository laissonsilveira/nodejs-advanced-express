# nodejs-advanced-express

Advanced techniques that will enable us to tackle more complex projects with Express

[Link to project example this course](https://github.com/laissonsilveira/nodejs-advanced-express/tree/main/)

## project skills

* Creating a template engine
* Using MongoDB and Mongoose for user management
* Authenticating and authorizing users
* Adding cookies and sessions to Express
* Creating a login form with Passport
* Handling file uploads
* Storing and serving images
* Deploying an Express application
* Securing an Express application
* Running behind a web server

### Tuning Express performance: Further measures
-----------------------------------------------

Futher Recommendations

* Cache request results
* Don't use synchronous funcions
* Don't use console.log() because it's synchronous
* Handle erros and exceptions properly
* Use a cluster

### Tuning Express performance: NODE_ENV and compression
-----------------------------------------------

Use `NODE_ENV=production` to reduce the CPU and more

Compress Server Responses

`npm add compression`

and use...

```javascript
const compression = require('compression');
const express = require('express');
const app = express();
app.use(compression());
```

### Securing an Express application
-----------------------------------------------

https://expressjs.com/en/advanced/best-practice-security.html
