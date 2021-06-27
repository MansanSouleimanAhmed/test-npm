
C => Stands for command that I ran in the terminal.

I : Means that something was install


## Env / Installation Npm+Gulp / Initialisation Gitflow

### Server that runs the project on the localhost
C => npm init -y


I: packagejson file

I dowloaded the file from this link/

https://www.npmjs.com/package/parcel-bundler

C => npm start      

To run the project on localhost.

Go on localhost:1234

To see the project on the browser.

### Gulp

What is Gulp? One description is that Gulp is a task runner. Another would be that it’s a toolkit for automating time-consuming tasks.

In the gulpfiles.js there are functions that triggered when you run gulp in the terminal.

I configured gulp so it watches the style.css file and the js file.

That each time you make any changes to one of those files gulp will update the browser without refreshing the page.

I also configured to minify all the images, and process a sass file into css.

### Git flow

The is workflow that helps us avoid the problemes that with merging to the master branch.

C=> git init
    git flow init [ master / features / bugfixe / hotfix /support []]
