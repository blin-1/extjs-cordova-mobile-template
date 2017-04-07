Sencha and cordova commnads to create and run this app

To Create :
cd yourWebRoot
sencha -sdk /path/to/sdk generate app -c MyController -v MyView -modern MyApp .

--------------------------------------
To Run in Dev mode:

  sencha app build development
  sencha app watch

--------------------------------------
Packaging to device

sencha cordova init com.me.MyApp MyApp
cd cordova
cordova add platform android -- save

To emulate/build
--------------------------------------
sencha app build production
sencha app build native
cordova emulate
