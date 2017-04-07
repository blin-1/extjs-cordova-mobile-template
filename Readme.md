Required :

Sencha Cmd, Android SDK, Cordova and Node installed

---------------------------------------
Sencha and cordova initialization

    sencha -sdk /path/to/sdk generate app -c MyController -v MyView -modern MyApp /path/to/yourBaseDir

    sencha cordova init com.me.MyApp MyApp
    
    cd cordova
    
    cordova add platform android -- save

----------------------------------------
To run in dev mode
--------------------------------------

  sencha app build development

  sencha app watch

--------------------------------------
To run on phone emulator with android SDK
--------------------------------------
  sencha app build production

  sencha app build native
  
  cordova emulate
