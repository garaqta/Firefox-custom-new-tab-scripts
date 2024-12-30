# Custom new tab for Firefox

An attempt at having a local custom homepage display on Firefox when opening a new tab. It supports custom CSS and JS files without the need of extensions or self hosting solutions, although it's a bit finicky and won't work if you open a new window, as it's specifically meant to work for new tabs.

### Usage

Move `autoconfig.js` to the `/MozillaFirefox/defaults/pref` folder. Then, move `autoconfig.cfg` to the root `/MozillaFirefox` folder and edit line 7 of the code with the path to your custom start page.
