# ionic 1


```sh
# step1: Install Ionic
$ npm install -g cordova ionic

# step2: Start a project
$ ionic start myApp blank 

$ ionic start myApp tabs 

$ ionic start myApp sidemenu

# step3: Run it
cd myApp

ionic platform add ios
ionic build ios
ionic emulate ios
# or
ionic platform add android
ionic build android
ionic emulate android
# or
ionic platform add browser
ionic build browser
ionic emulate browser


``` 