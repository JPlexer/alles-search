# Alles Search
This is a Fork of [privacytools-io-search](https://gitlab.com/nitrohorse/privacytools-io-search/)

Web extension that adds [search.alles.cx](https://search.alles.cx) as a search engine to the Firefox and Chrome browser (using the [
chrome_settings_overrides](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/chrome_settings_overrides) manifest key). Submits the query via GET request for compatibility with [Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/).

## Download
* To be done

## Develop Locally
* Clone the repo
* Install tools:
	* [Node.js](https://nodejs.org)
	* [nvm](https://github.com/nvm-sh/nvm)
* Use specified Node version:
	* `nvm use`
* Install dependencies:
	* `npm i`
* Run add-on in isolated Firefox instance using [web-ext](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Getting_started_with_web-ext) (open the [Browser Toolbox](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox) for console logging):
	* `npm start`
* Package for distribution:
	* `npm run bundle`
* To package for Chrome look at this: http://www.dre.vanderbilt.edu/~schmidt/android/android-4.0/external/chromium/chrome/common/extensions/docs/packaging.html