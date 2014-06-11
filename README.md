# Cordova hooks to produce working app
---

[CB-5634 screen orientation fix](https://issues.apache.org/jira/browse/CB-5634) *Dirty* Android, WP8

[Fixed for Cordova 3.5.0](https://gist.github.com/LinusU/7515016)

## Usage

Put package.json in your Cordova Application root folder, ```root```. Edit it, changing the name and author if you wish.

Put ```me.apla.cordova.hooks.js``` and the ```after_prepare``` folder in ```root/hooks```.

Go to ```root``` and type:

```npm install```

That's it.

*Note*: if you're developing for WP8 using VS2012 you have to type:

```npm install --msvs_version=2012```