Technologies
-----
Project created with:
* gradle version: 7.4,  setted in "path" env
* jdk version: 1.8.0,  setted in "path" env
* android studio : Chipmunk 2021.2.1

Environment variables
-----
* JAVA_HOME: \jdk
* Path: %JAVA_HOME%\bin; \gradle\bin; \Android\Sdk

Vue part
-----

### Project setup
```
npm install
```

### Lints and fixes files
```
npm run lint
```

### Compiles and minifies for production
```
npm run build
```

### Compiles and hot-reloads for development
```
npm run serve
```

Cordova part
-----
### Make cordova folder
```
cd ..
cordova create toolset-app com.wasichris.toolset toolset
```

### Add android@8.0.0
```
cd  toolset-app
cordova platform add android@8.0.0
```

### Build and emulate
```
cordova build android
cordova emulate android
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
