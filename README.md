AnimationProgressBar
===========
Android Studio version: 2.1.3
Gradle version: 2.1.3

The Latest Version
------------------
VersionCode 1
VersionName "1.1"

Project description
-------------------
This module implements the animated progress widget with percent indicator.
 
 ![](https://github.com/brezenhem/AnimationProgressBar/blob/master/screen_1.gif)
 
Install
----------

Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

Step 2. Add the dependency
```
	dependencies {
	        compile 'com.github.brezenhem:AnimationProgressBar:1'
	}
```

How to use
----------
```
To use the widget, simply add this code to your xml layout:

<lindenvalley.de.customprogress.AnimationProgressBar
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/progress" />

To update the indicator, simply call the following method:

AnimationProgressBar mAnimationProgressBar = (AnimationProgressBar) findViewById(R.id.progress);
mAnimationProgressBar.updateProgressIndicator();
```
