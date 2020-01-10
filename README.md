# Get-current-location-using-google-api-and-places-api

First, you need to create a Google API with apikey to login in GoogleAPI with your id. They provide you one apikey and put that in 
android manifests file using meta-data

![](images/apikey.png)

## Dependency

--in `build.gradle` app

![](images/library1.png)

**Dexter** is an Android library that simplifies the process of requesting permissions at runtime.
The official API is heavily coupled with the Activity. 
Dexter free our permission code from your activities and lets you write that logic anywhere you want.

**Google play services map** allow us to use all google map features

**Library places** library allow us to search different places according to our search

--in `build.gradle` project

make sure **maven** library is added to our project

![](images/library2.png)

## Screenshots

Here I simple request the permission to access the device's location


<img src="images/apiScreenshot.png" width="350" height="700">     <img src="images/apiScreenshot2.png" width="350" height="700">

After click `Allow`, it will directly bring to the MainActivity class where it shows the currect location of the user. If we click 
direction floating image right side <img src="images/nav.png" width="30" height="30">  of the screen then it also shows the current loaction

<img src="images/apiScreenshot3.png" width="350" height="700">

In `Search a place` search bar we can also search the placeses by clicking on it.

<img src="images/apiScreenshot4.png" width="350" height="700">

After entering a place the navigation icon will directly jump to the searched place in the map.

<img src="images/apiScreenshot5.png" width="350" height="700">

