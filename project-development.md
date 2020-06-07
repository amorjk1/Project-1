

# Project Development

## 27/02/2020

Got the gitlab working but seems like the code they pushed in to gitlab isn’t the latest one as it was not working at all when we tried them. We tried to fix by googling the error like the mismatch version, npm install and such. Still no luck

## 02/03/2020

Made the Kanban board for our project, also made and closed the project called "Sprint 1"

![sprint1](https://github.com/amorjk1/Project-1/blob/master/assets/images/development1.png?raw=true)

but since that we have an updated version of the nodes, we always get an error everytime we create a new branch on github.

![error](https://github.com/amorjk1/Project-1/blob/master/assets/images/development2.png?raw=true)

but we fixed it by putting the code below.

```js

var sharedBlacklist = [
  /node_modules[\/\\]react[\/\\]dist[\/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
```

[back](./)
