# learning-web-perf
Learning Website Performance Optimization.

## Table of contents

* [How the browser constructs a page?](#how-the-browser-constructs-a-page)
* [To dos for a better performance](#to-dos-for-a-better-performance)
* [Debugging Websites](#debugging-websites)
    * [Debugging Tools](#debugging-tools)
    * [Configuring Chrome debugging in Android devices](#configuring-chrome-debuggin-in-android-devices)
* [Web Performance Tools](#web-performance-tools)
* [Additional Reading](#additional-reading)

---

## How the browser constructs a page?

...

## To dos for a better performance

:point_right: Always analyze your website in your phone.

> Why? - Cellular phones are much more limited in features: slower CPUs, less RAM and GPU memory, higher connection latencies, etc. As a result, you'll always need to analyze and debug your site on mobile hardware to get a more accurate sense of the experience users will have on your site on mobile devices.

:point_right: ...
:point_right: ...

## Debugging Websites

### Debugging Tools

* [Chrome Canary](http://www.google.com/intl/en/chrome/browser/canary.html) - Chrome for Developers.

### Configuring Chrome debugging in Android devices

All you need is an Android device and a USB cable, so follow the steps below:

* Enable the Developer Mode in Android
    * Go to Settings > About Device > Click on "Build Number" 7 times.
* Next, enable USB Debugging in "Developer Options"
* Make sure you have Chrome installed in your laptop/PC (Chrome Canary, for instance) and in your cell phone.
* Open Chrome in your laptop/PC and type `chrome://inspect` in your browser input.
* Make sure that the website you are going to debug is open in Chrome (on your mobile device) and connect the USB cable in both (laptop and cellphone). Allow the USB connecting accepting confirming the modal that shows in your mobile device.
* Now, you could see the mobile device connected in Chrome on your laptop/PC. Type the website address which you want to debug.
* After that, you will have some controls like `inspect`, `focus tab`, `reload` and `close` the website you want, and will be able to start the debugging.

> TIP : When you are inspecting the website in Chrome Dev Tools with the mobile device connected, you can enable `screencast` in Developer Tools (phone icon, at the top left corner) in order to mirror the device screen in Chrome Dev Tools to facilitate the debugging process.

## Web Performance Tools

* [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/) - This tool from Google analyze and generate suggestions in order to improve your website performance.

## Additional Reading

* [Perf Rocks](http://perf.rocks/)
* [Page Speed rules and recommendations](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/page-speed-rules-and-recommendations)