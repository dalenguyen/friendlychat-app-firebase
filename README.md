Friendly Chat App By using Firebase

This app will use Google Sign in for logging in. User can chat and upload images.

Demo: https://friendy-chat-dn.firebaseapp.com/

# Prerequisites

Clone this git repository

```
git clone https://github.com/dalenguyen/friendlychat-app-firebase.git
```

Install Firebase Command Line Interface

```
npm -g install firebase-tools
```

Login into to your account

```
firebase login
```

Add this directory to your firebase project

```
firebase user --add
```

Before that, you need to

* You have to create a project in Firebase.
* Enable Authentication through Google
* Start Storage for saving images

# Deploy and run the web app

Deploy this chat app without functions. You will find the Hosting and Project Console after running this one.

```
firebase deploy --except functions
```

# Testing this project 

You now can got to the Hosting URL and start using it.


*This repository follows [Firebase SDK for Cloud Functions Codelab](https://codelabs.developers.google.com/codelabs/firebase-cloud-functions/).*
