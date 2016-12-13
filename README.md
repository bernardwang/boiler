# starter
boilerplate with es6, browserify, gulp and other goodies.

## getting started

##### 1. clone this repo

##### 2. install gulp globally
```
npm install -g gulp
```

##### 3. install dependencies
go to the project folder you just downloaded and run:
```
npm install
```
##### 3. do it
```
gulp dev
```

## gulp commands

`gulp dev` - builds project into the `/dist` folder, automatically watches for changes and reloads page.

`gulp prod` - lints your javascript and builds a minified project.

`gulp deploy` - deploys project to github pages after building prod project.

also useful:

`gulp min-imgs` - compresses and moves images from `/src/assets/img/` to the `/dist` folder (caution: takes a while)

`gulp clean` - deletes the `/dist` folder so you can rebuild from scratch.