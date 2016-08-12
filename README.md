# ionic-with-ionic-native
example for ionic-native plugins

Created via:

```
ionic start ionic-testapp tabs 
bower install ionic-native --save
ionic plugin add cordova-plugin-network-information
```

Warnings on the console when `ionic emulate ios`:

```
[Warning] Native: tried calling Network.connection, but the Network plugin is not installed. (ionic.native.js, line 9339)
[Warning] Install the Network plugin: 'ionic plugin add cordova-plugin-network-information' (ionic.native.js, line 9344)
```
