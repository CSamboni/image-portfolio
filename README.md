# image portfolio

> A Vue.js + Firebase project

show off pictures using Vue.js as the framework and Firebase as the backend.

<a href="https://mjduplinsky.firebaseapp.com">https://mjduplinsky.firebaseapp.com</a>

## Before anything else...

To get setup you need a Firebase app.

The Firebase rules are as follows:

```
{
    "rules": {
        "users": {
            ".write": true,
            ".read": true
        },
        "images": {
            ".write": true,
            ".read": true
        },
        "image_index": {
            ".write": true,
            ".read": true
        }
    }
}
```

Also add a user under `Login & Auth`

## Setup & Deploy


Do a `find & replace` across all files, including .vue files for `portfolio` & `firebaseio.com` & `firebaseapp.com` then replace all of these with your own information. 


To deploy to Firebase, change to your Firebase app, you can then run
`npm install` to install all dependencies and `npm run deploy` to build your app and deploy to firebase.

```
  //firebase.json
  "firebase": "portfolio",
```

## Local Dev

To run locally `npm run dev`

## Help

<a href="https://www.firebase.com/docs/hosting/quickstart.html">https://www.firebase.com/docs/hosting/quickstart.html</a>
