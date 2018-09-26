
# Meteor Overview

## Technologies

* NodeJS - https://www.nodejs.org
* Meteor - https://www.meteor.com
* React - https://reactjs.org
* MongoDB - https://www.mongodb.com
* Apache Cordova - https://cordova.apache.org/

## Basic Meteor Setup

Meteor is a web application framework that allows you to create an app that runs in both a server and a client 
context. When your app is run/deployed, it will run as a nodejs backend while the client side is delivered as 
a javascript web app.

It also has built in support for Apache Cordova which allows the client side of the app to be built as an
iOS/Android app using cordova. The build process produces an XCode project for iOS which can be compiled and
sent to the App Store, and for Android it generates an Android Studio project and actually creates an apk
file automatically which can be uploaded to the Google Play store.

- Install Chocolatey - https://chocolatey.org/install
- Install Meteor - https://www.meteor.com/install
- Create Bare Project - https://docs.meteor.com/commandline.html#meteorcreate

## UI Framework

Meteor does not include a UI framework of any sort, although it does come with an html templating system which
can be used out of the box (Blaze). However, it is easy to add react to meteor to start building the UI using
a component based architecture.  

- Add React - https://guide.meteor.com/react.html

But even with React installed, native feeling UI components still need to be designed from scratch. This is why
a UI framework can make creating UI components much easier.

- Framework7 (React) - http://framework7.io
  - http://framework7.io/docs/installation.html
  - http://framework7.io/react/installation.html
  
- Ionic (Angular) - http://ionicframework.com
  - https://github.com/urigo/angular-meteor
  - https://github.com/meteoric/meteor-ionic

## Meteor Fundamentals

- Meteor uses DDP (sockets) to provide client/server communications
  - Data sets can be pushed to clients as they change on the server using a pub/sub model.
  - Data can be requested by the client from the backend using 'Methods'.
  
  

