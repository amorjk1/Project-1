

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

under \node_modules\metro-config\src\defaults\blacklist.js

I have talked with Renz (previous developer of the project) and he said to use his branch instead of Camerons one as it was the only one working on their GitLab. We tried it and got the same error that says that it cannot find the Java Compiler.

## 05/03/2020

We realized that the reason why the app is not working is when they pushed the project into gitlab, it didn't upload the modules with it so to fix this, we had to install it by typing "npm install" then make a new variable “Java/home” then “C:\Program Files\Java\jdk-11.0.5” 

then under user variable, make a new one called "ANDROID_HOME” then value will be “C:\Android\SDK”

then restart the computer

under “node_modules” you will open “metro-config” then “src” then “defaults” then open up blacklist.js and make sure you add the \ to the code like the example below.

#### Before

```js
var sharedBlacklist = [
  /node_modules[/\\]react[/\\]dist[/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
```

#### After

```js
var sharedBlacklist = [
  /node_modules[\/\\]react[\/\\]dist[\/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
```


## 12/03/2020

had to do the about page for this project and followed this <a href="https://www.youtube.com/watch?v=0h2TLGJya4A">YouTube</a> tutorial and it actually helped me understand more about React-native.

few things to consider:

#### to run it on the simulator.
_npx run react-native run-android_

#### to run it on my phone.
_npx run react-native start_

## 16/03/2020

We have added a GitHub widget to our Microsoft Teams Group Project for us to easily check on the current issues we have in the actual project.

I had to create another image for the "About us" page since it does not have a proper image for it at the bottom navigator view.

Managed to do the "About us" page, Aisea emailed Josh Perry about it and quite happy of what we've done so far.

## 22/03/2020

I had to go back to Wellington for a week, during this time I was just reading online on how to improve react-native skills and other tutorials on how to use it.

# Code Evidence

![evidence1](https://github.com/amorjk1/Project-1/blob/master/assets/images/codeEvidence1.PNG?raw=true)

![evidence2](https://github.com/amorjk1/Project-1/blob/master/assets/images/codeEvidence2.PNG?raw=true)

![evidence3](https://github.com/amorjk1/Project-1/blob/master/assets/images/codeEvidence3.PNG?raw=true)

![evidence4](https://github.com/amorjk1/Project-1/blob/master/assets/images/codeEvidence4.PNG?raw=true)


[back](./)
