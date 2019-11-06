
# FabNavigation
Library to implement the Bottom Navigation component from Material Design guidelines (minSdkVersion=21).

## Demo
<img src="https://user-images.githubusercontent.com/29139786/68336532-9fc1da00-0104-11ea-84f5-a6827c861cfb.gif" width="208" height="368" />

## Features
* Follow the bottom navigation guidelines (https://www.google.com/design/spec/components/bottom-navigation.html)
* Add 3 to 5 items (with title, icon & color)
* Choose your style: Classic or colored navigation
* Add a OnTabSelectedListener to detect tab selection
* Support icon font color with "setForceTint(true)"
* Manage notififcations for each item
* Enable/disable tab state

## How to?

### Gradle
```groovy
dependencies {
    implementation 'com.github.aggarwalpulkit596:FabNavigation:1.0'
}
```
### XML
```xml
    <com.codingblocks.fabnavigation.FabNavigation
        android:id="@+id/bottom_navigation"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="bottom"
        app:selectedBackgroundVisible="false" />
```


## Contributions
Feel free to create issues / pull requests.
