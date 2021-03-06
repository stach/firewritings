# Firewrite 0.2.0
[![forthebadge](http://forthebadge.com/images/badges/uses-html.svg)](http://forthebadge.com)

A blogging system builted on Firebase Realtime Database.
To setup Firewrite, take a look at the setup's [readme](https://github.com/stach/firewrite/blob/master/setup/readme.md).

## Inserting Configuration
You will insert the configuration that you got from Firebase into `src/config.js`.

##### Example Firebase Configuration
```
var config = {
    apiKey: "XXX",
    authDomain: "XXX",
    databaseURL: "XXX",
    projectId: "XXX",
    storageBucket: "XXX",
    messagingSenderId: "XXX"
};
firebase.initializeApp(config);
```

I recommend using [JavaScript Obfuscator](https://javascript-obfuscator.org) to encrypt your configuration, just like I did.

## Caught a Bug?

1. [Fork](https://help.github.com/articles/fork-a-repo/) this repository to your own GitHub account and then [clone](https://help.github.com/articles/cloning-a-repository/) it to your local device
2. Move into the repository's directory: `cd firewrite`
3. Run [live-server](https://www.npmjs.com/package/live-server)

## License

Firewrite is licensed under the MIT License. You can view the `license.md` file [here](https://github.com/rdstach/firewrite/blob/master/license.md).
