# ngx-do-api-gateway is a Mock API Server
This packages is there to run a mock json base API/DB server with authentication, authorization, ddos protection and auto rebuild of database base on the different data files. **Don't use it for production services.**

To start the server use ```node index.js``` or ```npm start --silent -- ``` and for example to override the port configuration variable add ```--port=3001```

To create a api or password key use node **index.js --generateKey="your the secret"**


# Deploying it on zeit.co
If you need hosting of this proxy zeit.co offer 3 free instances you can use as follows.

Install now globally

```
  sudo npm install now -g
```

Publish the db server to zeit
```
now --public
now alias [url from now] [alias]
```

Removing from zeit

```
now rm [url from now or alias-doit]```

