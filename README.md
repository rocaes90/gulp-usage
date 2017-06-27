# gulp-usage

## ABOUT THE APP
this files is an example about how to implement gulp into a project

## WHAT TECHNOLOGIES ARE using
-gulp

## ABOUT STRUCTURE
```
1. GULP - FOLDER: gulp-tasks to copile and create the dist of the application
    1. tasks.js - FILE: has tasks for 
        - copy files
        - build (files, sass, ts, html)
        - watch
        - serve (developer version/only run server with the precompiled version)
        - clean
```

## RUN INDICATIONS

#### clean commands
```
gulp clean:all - delete all from app and node_modules folders
gulp clean:nm - delete all from node_module folder
gulp clean - delete all from js folder and html (components)
````
#### build commands
```
gulp build - make a build for the application 
```

#### serve commands
```
gulp serve:dev - execute the clean, build and start the server
gulp server:only - run the server, using the precompiled code
```
