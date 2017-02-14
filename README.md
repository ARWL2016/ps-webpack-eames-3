##Webpack Fundamentals
###Part 3: Webpack Connect Middleware   


###Packages 
- ejs  
- express  
- morgan (the logging package for express)
- webpack-dev-middleware  https://github.com/webpack/webpack-dev-middleware 


---
###Server Options
- The Webpack Connect Middleware can be used with Node and Express 
- Other backends could be used with webpack in watch mode 
- WDM is a way to create a development server while using express  
- We do this with an if statement in server.js. If `env` is set to 'development' it will add properties to `webpack.config`. This way we don't need to change the config file. 
- Using WDM, we must define the 'publicPath'  
- Using this setup we can run `node server.js` and it will build the bundle


  