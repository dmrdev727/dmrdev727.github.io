## DMR Launcher
Currently in open testing on Google Play. DMR Launcher is a solo effort from someone who wants more functionality available in their android launcher!
<!-- Blank line here -->

## Why?
DMR Launcher is built for people who want to efficiently navigate their android experience, packed with useful features and theme options.
+ Powerful Search - find apps, system settings, app shortcuts, every app activity, or launch a web search.
+ Clean Design - Display your wallpaper front and centre or save power with a black background.
+ Configurable - Set up the Dock to be perfect for you with Apps, Website Shortcuts or Folders. Quick muscle memory access to your favourite apps. No non-sense 3rd parties deciding where your apps should be.
+ Predictable - The App Drawer is setup as horizontal pages to help you build easy muscle memory to navigate.
+ Customisation - Choose a launcher-wide background and accent colour. Toggle the wallpaper. Adjust icon saturation and size. Select your exact colours with a hex code.
+ Flexible - Adjust the App draw density as you see fit.
+ Website Shortcuts - Add website URLs directly to your App Drawer, bypassing Web App limitations. Avoid installing excess applications to you device.
+ Pinned Shortcuts - Supports Add to Homescreen from other applicaitons.
+ Categorisation - Create your own categories and assign apps and website shortcuts to category pages in the App Drawer.
+ Screen Burn In Protection - Home screen elements move slightly at regular intervals to help avoid clear screen burn in for OLED and AMOLED displays.
+ Repeated Use Visual Queues - By adjusting the colour saturation of the app icons, the DMR Launcher can help break your app addiction.
+ Hide Apps - Clean up the app drawer by hiding unwanted applications.
+ Simple and Fast - Select your preferred animations or disable entirely.
+ Widget Support.
+ Notification indicators.
<!-- Blank line here -->

## DMR Launcher vs DMR Launcher Pro?
All features are available in both apps however I update and test the Pro app first.<br/>
DMR Launcher contains Google Admob advertisements in the App Drawer and Search Screen.<br/>
DMR Launcher Pro contains no advertisements.
<!-- Blank line here -->

## To-Do List
1. The Notification Bar Style setting should not apply to the App Drawer.
2. Shortcut to add a permanent Web Shortcut from a Search History record of a manually typed URL.
3. Update the controller / keyboard navigation on the Home Screen to work nicely when the Navigation Buttons are enabled.
4. Investigate further Screen Reader & Accessibility options.
5. Widget overhaul (multiple widgets, multiple pages of widgets)
6. Publish the Pro app to F-Droid (someday hopefully)
<!-- Blank line here -->

## Design Decisions
1. Fundamentally, this launcher reflects how I like to setup my phone with configuration options available to setup the launcher in several other ways. My preferences are:
+ One row of icons and folders at the bottom of the home screen for easy access one handed.
+ App drawer displayed in fixed grid pages so I can built muscle memory to open apps quickly.
2. I have built in functionality that allows me to use my phone quicker:
+ I want the ability to add a specific URL as a Web Shortcut, not just a generic link to the website, a specific url.
+ A local search with access to app shortcuts and app activities. With the option to launch a web search in my default browser using my default search engine!
3. To ensure the app uses the least memory and processing possible, App icons are loaded in lazily. Meaning they are only loaded into memory when they are shown on screen which can result in a slight hitch on the first load of a App Drawer page etc. The benefit is that the app does not waste processing time or memory on icons you have not seen. The app then removes the icons from memory if the android system asks for memory space to be cleared.
4. I have tried to ensure the whole app is navigable by controller, keyboard inputs, or screen reader inputs. Let me know if there is anything I can improve.
<!-- Blank line here -->

## Contact

[Email me your feedback and ideas at dmrdev727@gmail.com](mailto:dmrdev727@gmail.com)
