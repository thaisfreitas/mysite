---
layout: post
title: "Thais Freitas, Build node js app guide by tests"
date: 2018-02-07
---

## Let's build node.js web app guide by tests?

You can see the code of this tutorial on [GitHub](https://github.com/thaisfreitas/thaisfreitas/edit/master/index.md) 

### Goal of this post 

The propose of this post is to setting up a project to build a web application guide by tests. 

### Start the Project

Create a directory and run the following command:

`$ npm init`

After that some question about the project will be displayed for you anwser, don't worry if you don't have all the awnser now you will can update it latter.

In consequectly a file called `packege.json` will be genareted on the root of the project. 


### Support to ES6

Installing all packages and setting up _Babel.js_:

`$ npm install --save-dev babel-cli`

Let's use the _preset_ to be able to use _ES6_:

`$ npm install --save-dev babel-preset-node6`

**PS:** `--sav-dev` will save this as a development dependencies.  

To finish the _Babel_ setting up let's create a file in the root of the project called `.babelrc` with the following informations:

`{"presets" : ["node6"]}`

### Setting up the web server
To developer a web application we will need to have a server that will help us to do _HTTP_ requests, data transferring, routs and more. 
Let's use Express.js to do it in our case, but 

There are options available to do the same work.

`$ npm install --save express body-parser`