this project is simple project to create a new cli for react app project.

Instead of using create-react-app cli, we can create our own cli.

added loaders to handle css, so that babel can transpile css as well.

please follow the below url for generating a new react cli.

https://medium.freecodecamp.org/part-1-react-app-from-scratch-using-webpack-4-562b1d231e75

https://www.youtube.com/watch?v=deyxI-6C2u4

note: babel-loader is having some dependency with babel 7.x, so better use babel-loader 7.x

To start this project, clone the repo execute below commands
  1 npm install : installs all the dependencies
  2 npm start : starts the webpack dev server in development mode and open the browser instance with hot module reload
  3 npm build : builds the app in the production mode which is a minified version of the code and places it in the lib folder.
