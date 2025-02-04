# Duolingo Language Course Switcher

This userscript for [Duolingo](https://www.duolingo.com/) simplifies switching your UI language.

It uses [local storage](https://en.wikipedia.org/wiki/Web_storage) to track your courses, it may not work as expected if you clear your browser's data.

## Course Switcher is dead!

This script became useless since duolingo implemented quickly changing languages.

### Installing

1. If haven't already, install the appropriate extension for your browser (restarting your browser afterwards if necessary):
 * Chrome: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
 * Chromium: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
 * Firefox: [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
 * Safari: [JavaScript Blocker](http://javascript-blocker.toggleable.com/)
2. Click [here](https://github.com/arekolek/DuolingoCourseSwitcher/raw/master/duolingo-course-switcher.user.js) to install the userscript.
3. Confirm the installation when prompted.

### Usage

* Use Duolingo as you normally would.
* Language menu shows all languages used since installation of this script.
* Effectively, you need to switch the old way *once* for any base language you use.

### Uninstalling

1. Follow the uninstall steps for the browser/extension you're using:
 * Chrome: [Tampermonkey](http://tampermonkey.net/faq.php?ext=dhdg#Q101)
 * Chromium: [Tampermonkey](http://tampermonkey.net/faq.php?ext=dhdg#Q101)
 * Firefox: [Greasemonkey](http://wiki.greasespot.net/Greasemonkey_Manual:Script_Management)
 * Safari: [JavaScript Blocker](http://javascript-blocker.toggleable.com/)

### Screenshots

Right after installation, Duolingo showing courses from English:

![before](http://i.imgur.com/IiMXFmy.png)

After switching to Spanish interface, the script remembered English courses and updated the language menu.

![after](http://i.imgur.com/gkOOGxW.png)
