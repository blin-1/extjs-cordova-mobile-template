
----------------------------------------
<h2>Required dependencies</h2>

    Sencha Cmd, 
    Android SDK, 
    Cordova,
    Node

----------------------------------------
<h2>Project initialization in empty yourBaseDir</h2>
    
    (already done here, but you should really redo this on empty baseDir )

    sencha -sdk /path/to/sdk generate app -modern MyApp /path/to/yourBaseDir
    sencha cordova init com.me.MyApp MyApp
    cd cordova
    cordova platform add android -- save

----------------------------------------
<h2>To run in dev mode</h2>

    sencha app build development
    sencha app watch

--------------------------------------
<h2>To run on phone emulator with android SDK</h2>
    
    sencha app build production
    sencha app build native
    cordova emulate
