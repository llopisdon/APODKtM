![apodktm logo](app/src/main/res/mipmap-hdpi/ic_launcher_foreground.png)

# Astronomy Picture of the Day + Kotlin + Material Design (APODKTM)


A sample Android app that stores and displays the NASA Astronomy Picture of the Day (APOD) for each month.

![screenshot](assets/screenshot.png)

The app demonstrates the use of the following technologies:

* Coil
* Hilt
* Kotlin
* Kotlin Coroutines
* Kotlin Flows
* Jetpack Architecture Components
* Jetpack Navigation
* Jetpack Room
* kotlinx.serialization
* Ktor
* Material Components for Android


# APOD API KEY

The app looks for an APOD api key in this properties file:

```
~/.gradle/gradle.properties
```

The api key property key/value pair should be defined as:

```
apodktm_nasa_apod_api_key=<YOUR API KEY>
```

If an APOD api key is not found then the demo APOD api key is used:

```
DEMO_KEY
```

To generate an APOD api key go here:

https://api.nasa.gov/


# Resources

## NASA APOD

https://apod.nasa.gov/

## NASA APOD Api Reference

https://github.com/nasa/apod-api

## Icon & Place Holder Image

**"Very Large Array, Socorro, United States"**

https://unsplash.com/photos/Wj1D-qiOseE

*By Donald Giannatti*

