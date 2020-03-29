# Starter-Kit-2020

Built for speeding up the process of web development. 

**Steps**
---------

 **Install Node**
	https://nodejs.org/en/

 **Install all the node packages** 
On the root of this project run on your terminal.
    
    npm install
    
 **Update the node packages** 
On the root of this project run on your terminal.
    
    npm update

**Start the scss conversion plus lite-server**

  npm start

 **Start building distribution folder (copyfonts, imagemin, usemin)** 
1.You will need to edit "usemin" in package.json to include all html files.
2.Surround the css links and js scripts with inclusion code "build:css css/main.css" and "build:js js/main.js" in all html files.

  npm run build
