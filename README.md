# Covid Weather

**An Android app that showed the Covid-19 situation in your Slovenian municipality as a weather forecast: sunny when cases were falling, rainy when they were rising.**

During the pandemic, case numbers were everywhere, but hard to read at a glance. Covid Weather turned them into something everyone already understands: the weather. The original Slovenian name was *CovidVremenar*.

<p>
  <img src="https://user-images.githubusercontent.com/57682513/138561628-e4d73cf7-2513-41f2-a5bd-3765b2c0bebe.jpg" width="260" alt="Rising cases shown as rainy weather">
  &nbsp;
  <img src="https://user-images.githubusercontent.com/57682513/138561668-6cb949a9-da10-43ac-aa76-7a9540af41e0.jpg" width="260" alt="Falling cases shown as sunny weather">
</p>

## Features

- **Your municipality:** pick it from a list, or let the app find it from your location.
- **Weather metaphor:** active cases rising means rain, falling means sun.
- **Key numbers:** population, active cases and new cases for the selected municipality.
- **Vaccination:** first and second doses given today and to date, with charts.
- **Slovenia overview:** the national picture, embedded from Covid-19 Sledilnik.

## How it was built

- **Design:** the interface was designed in Adobe XD first, then built natively.
- **App:** Java in Android Studio (Android 4.1 and later), with Material Components and MPAndroidChart for charts.
- **Data:** the public REST API of [Covid-19 Sledilnik](https://covid-19.sledilnik.org), Slovenia's volunteer-run Covid tracker.
- **Location:** Google Play Services, used to pick the municipality automatically.

## Run it

Open the project in Android Studio and run it on a device or emulator.

Note that the app depends on the Sledilnik API, so the numbers it shows depend on that API still being available.

## Credits

Built by **Eva Vidmar** and **Matjaž Bevc** for the *Terminal Devices and User Interfaces* course at the Faculty of Electrical Engineering, University of Ljubljana (2021). It received the highest grade in the course.

---

*University project (2021), not actively maintained.*
