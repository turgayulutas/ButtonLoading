# ButtonLoading
<br/><br/>
Beautiful Fancy Button Loading<br/><br/>
[![](https://jitpack.io/v/rasoulmiri/buttonloading.svg)](https://jitpack.io/#rasoulmiri/buttonloading)
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Button%20Loading-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/6394)
Minimum API 17
<br/><br/>
![Demo](https://raw.githubusercontent.com/rasoulmiri/ButtonLoading/master/demoFile/1.gif)

<br/><br/>



## Usage:
#### Step 1:

Add JitPack repository in your root build.gradle at the end of repositories.

    allprojects {
        repositories {
    	    ...
    	    maven { url 'https://jitpack.io' }
        }
    }
   
Add dependency in your app level build.gradle.

    dependencies {
	      compile 'com.github.rasoulmiri:buttonloading:v1.0.8'
	}

<br/><br/>
#### Step 2:
use in layout xml 

```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    
        //...
  
        <io.rmiri.buttonloading.ButtonLoading
            android:layout_width="match_parent"
            android:layout_height="48dp"
            app:BL_backgroundColor="#80ffffff"
            app:BL_circleColor="#00AFEF"
            app:BL_circleColorSecond="#8000AFEF"
            app:BL_enable="true"
            app:BL_stateShow="normal"
            app:BL_text="Login"
            app:BL_textColor="#FFFFFF"
            app:BL_textSize="14sp" />

    
</RelativeLayout>
```
<br/><br/>
#### Step 3:

```java
buttonLoading.setOnButtonLoadingListener(new ButtonLoading.OnButtonLoadingListener() {
            @Override
            public void onClick() {
           	//...
            }

            @Override
            public void onStart() {
               //...
            }

            @Override
            public void onFinish() {
               //...
            }
});
```
<br/><br/>
# Configure XML
 * **BL_backgroundColor** 
 * **BL_circleColor** color 
 * **BL_circleColorSecond**
 * **BL_stateShow:** normal,animationStart,progress,animationFinish | default value is normal
 * **BL_text:** text button
 * **BL_textColor** 
 * **BL_textSize**
 * **BL_font:** address font in assets. example: file in assetst > fonts > arial.ttf  ==>  fonts/arial.ttf
 <br/><br/>
 **Note: Do not use the button in LinearLayout.**
  <br/><br/>
 ## Contributing
 

You are welcome to contribute with issues, PRs or suggestions.


<br/><br/><br/>
## Other Project Me

# Skeleton Android
Simple yet powerful skeleton animation for all view in android 
<br/><br/>
![alt tag](https://github.com/rasoulmiri/Skeleton/blob/master/demoFile/1.gif)
<br/><br/>


<br/>
[Repository](https://github.com/rasoulmiri/Skeleton)
<br/>
