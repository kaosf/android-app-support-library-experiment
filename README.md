# Android app support library experiment

## References

* http://www.techdoctranslator.com/android/guide/activities/fragments

## Environment

* OS: Ubuntu 12.04 amd64
* JDK: OpenJDK 1.7
* Eclipse: Eclipse IDE for Java EE Developers (4.3 (Kepler))
* Apache Ant: 1.9.2
* Android SDK: r22.3-linux

## How was this created

1. Launch Eclipse
2. File > New > Other... > Android > Android Application Project
3. "New Android Application" wizard
    1. Create a new Android Application
        * Application Name: "support library experiment"
        * Project Name: android-app-support-library-experiment
        * Package Name: com.example.app
        * Minimum Required SDK: API11: Android 3.0
        * Target SDK: API18: Android 4.3
        * Compile With: API19: Android 4.4
        * Theme: Holo Light
    2. Configure Project (all default)
        * Create custom launcher icon: checked
        * Create activity: checked
        * Mark this project as a library: unchecked
        * Create Project in Workspace: checked
        * Working sets > Add project working sets: unchecked
    3. Configure the attributes of the icon set (all default)
        * Foreground: Image
            * Image File: launcher_icon
            * Trim Surrounding Blank Space: checked
        * Foreground Scaling: Crop
        * Shape: None
        * Background Color: "white"
    4. Select whether to create an activity, and... (all default)
        * Create Activity: checked
        * select "Blank Activity"
    5. Create a new blank activity, with... (all default)
        * Activity Name: MainActivity
        * Layout Name: activity_main
        * Navigation Type: Fixed Tabs + Swipes

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright 2013 ka
