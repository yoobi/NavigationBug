# Navigation components bug report

Reported on Android issue tracker: #[210687967](https://issuetracker.google.com/issues/210687967)

Component used: Navigation
Version used: 2.4.0-beta02
Devices/Android versions reproduced on: Multiple devices and versions

If this is a bug in the library, we would appreciate if you could attach:
- Sample project to trigger the issue: https://github.com/rekire/NavigationBug/ (this repo)
- A screenrecord: https://raw.githubusercontent.com/rekire/NavigationBug/main/screenrecording.mp4

The tab selection does not update as expected. I have two tabs called in my example Home (with a [`HomeFragment`](app/src/main/java/eu/rekisoft/android/navbug/HomeFragment.kt)) and Second (with a [`SecondFragment`](app/src/main/java/eu/rekisoft/android/navbug/SecondFragment.kt)). When I navigate from `HomeFragment` to [`HintFragment`](app/src/main/java/eu/rekisoft/android/navbug/HintFragment.kt) this works as intended, but when I switch the tabs from the button navigation the tabs do *not* update. This bug does not happen with the version 2.3.5