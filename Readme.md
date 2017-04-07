sencha -sdk /C/Users/Yuri/software/Sencha/ext-6.2.0 generate app -c Map -v Map -modern iPark .
sencha app build development
sencha app watch
--------------------------------------
sencha cordova init com.opensourceinc.iPark iPark

cd cordova
cordova add platform android -- save


emulate/build
--------------------------------------

sencha app build native
cordova emulate
