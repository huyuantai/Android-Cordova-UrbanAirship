Android-Cordova-UrbanAirship
============================

Android Cordova UrbanAirship is a successful example of using Cordova connects to the UrbanAirship.

You can make it works with the below steps


Requires
============================
* JDK
* Android SDK 4.2.2
* Eclispe or  [ADT](http://developer.android.com/sdk/index.html)  


Run it 
============================

This moment,we assume that you have already finish your Android Platform,
and make sure that you can run your first android project with it.

You have to use gcm in order to push notification,you can start it in here
[Gcm](http://docs.urbanairship.com/build/android.html#get-your-api-key-from-google) 

You will use UrbanAirship Services in order to communicate with gcm,you can get it here
[UrbanAirship](http://docs.urbanairship.com/dashboard/getting_started.html#registration-and-login) 

In above,you will get 

* gcmSender(Google API project number) 
* AppKey
* AppSecret 

cd to sample-app/assets

1.change the airshipconfig.properties.sample to airshipconfig.properties,and then configure your AppKey,AppSecret,and gcmSender

2.change the location.properties.sample to location.properties.

3.run the project 

    