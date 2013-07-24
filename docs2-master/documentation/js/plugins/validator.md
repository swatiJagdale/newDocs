Mobile starter Kit
================================

JS
--------------------------------
JS contains following components


Folder structure contains:
*[cordova] ().*  
*[jquery] ().*      
*[plugins] ().*      
*[require] ().*      
*[respond] ().*      

Cordova folder contains cordova dependencies for android and ios applications.

Depending upon which platform one wants to run the application (android or ios) on, 
cordova js files are to be renamed, removing the _ios or _Android suffix accordingly.
  

jquery folder contains following

*[jquery.mobile.config] ().*
*[jquery.mobile.custom.min] ().*

jquery.mobile.config refers to configuration properties of jquery mobile for our application

Properties are

1. defaultPageTransition  set to none
2. transitionFallbacks.slide set to none
3. pageLoadErrorMessage set to false
4. loadingMessage set to false

Plugins are

1. activityManager 
Responsible for pushing current activity in background.
Presents Home screen once application is minimised.

2. CompuwareUEM

3. googmaps
Its a plugin used to display map in the application.
4. infobox
Infobox js is used to show information on map about the location  with pointer.
5. iscroll
Iscroll is used to scroll the content of the page

6. jQuery.maskedInput
It is used to mask inputs  on andoid 4.0 and above devices

7. sessionManager
It is used to handle session of a user from login time.
8. validator
Contains all the validation functions.
9. webTrendCommon
10. WebTrendsDataCollector
Webtrend is used to track user's actions in the application in terms of navigation and activities which user performs.

require
It contains require.js dependency mainly, which is used to load other dependencies (scripts), it is useful in mvc structure of the application.

Contais a plugin folder
includes dependencies like 
i18n
async
text


respond

modernizr-2.6.1-respond-1.1.0

mustache

mustache provides dependencies for writing mustache files used in mvc structure