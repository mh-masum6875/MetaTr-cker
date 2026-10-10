# MetaTr@cker

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

A free, ad-free Android fitness tracker for working out at home. Users record their body measurements and training sessions and follow their progress day by day.

## Why

During the COVID-19 lockdowns gyms were off limits, and many fitness apps put useful features behind subscriptions. MetaTr@cker is a community project that keeps tracking free for everyone.

## Features

- Account sign-up and login
- Body-metric calculators: **BMI** and **FFMI**
- Track weight, body fat, muscle, water, and measurements (biceps, chest, waist, hips, thighs)
- Create and log custom workouts
- Dark mode, profile, privacy policy and contact pages

## Tech stack

Java, Android SDK (min SDK 21), Retrofit and Volley for networking, Firebase, Material Components.

## Project structure

```
app/src/main/java/com/example/meta/
├── LoginActivity, ProfileActivity, MenuActivity   # auth and navigation
├── Cal_BMI, Cal_FFMI, BMIRresult                  # calculators
├── CreateWorkout, PhysicalStats                   # tracking
└── Api, RetroClient, RequestHandler               # networking layer
```

## Build

1. Open the project in Android Studio.
2. Add your own `app/google-services.json` from your Firebase project.
3. Sync Gradle and run on a device or emulator.
