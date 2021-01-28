# fi

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 54 documents.
* Moved 30 document.
  * 7 orphaned documents.
  * 1 conflicting documents.
  * 22 renamed documents.

## Explainer

### Orphaned

Orphaned documents are documents that do not have a corresponding english
document (anymore). Their folder/slug has been prefixed with `orphaned`.
Redirects where added as there might me links to these documents.

### Conflicting

Conflicting documents are documents where the corresponding english document has
multiple translations. In this case we chose one of them (best effort) to be the
translation and prefixed the other candidates folder/slug with `conflicting`.

Some of the conflicting articles are a result of them being a translation of a
section like
[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators#assignment_operators].

### Renamed

Documents that had a localized slug or simply a slug mismatching the slug of the
corresponding english document.

## Full List of Changes

List of _old link to document on production MDN_
→ _new link to the document on dev_

### Orphaned

* [/fi/docs/demos/detail](https://developer.mozilla.org/fi/docs/demos/detail) → [/fi/docs/orphaned/demos/detail](/fi/docs/orphaned/demos/detail)
* [/fi/docs/demos](https://developer.mozilla.org/fi/docs/demos) → [/fi/docs/orphaned/demos](/fi/docs/orphaned/demos)
* [/fi/docs/fi](https://developer.mozilla.org/fi/docs/fi) → [/fi/docs/orphaned/fi](/fi/docs/orphaned/fi)
* [/fi/docs/Mozilla_Developer_Centerin_sisällöt](https://developer.mozilla.org/fi/docs/Mozilla_Developer_Centerin_sisällöt) → [/fi/docs/orphaned/Mozilla_Developer_Centerin_sisällöt](/fi/docs/orphaned/Mozilla_Developer_Centerin_sisällöt)
* [/fi/docs/Skinin_luominen_Firefoxiin/Aloittaminen](https://developer.mozilla.org/fi/docs/Skinin_luominen_Firefoxiin/Aloittaminen) → [/fi/docs/orphaned/Skinin_luominen_Firefoxiin/Aloittaminen](/fi/docs/orphaned/Skinin_luominen_Firefoxiin/Aloittaminen)
* [/fi/docs/Skinin_luominen_Firefoxiin](https://developer.mozilla.org/fi/docs/Skinin_luominen_Firefoxiin) → [/fi/docs/orphaned/Skinin_luominen_Firefoxiin](/fi/docs/orphaned/Skinin_luominen_Firefoxiin)
* [/fi/docs/Teemat](https://developer.mozilla.org/fi/docs/Teemat) → [/fi/docs/orphaned/Teemat](/fi/docs/orphaned/Teemat)

### Conflicting
* [/fi/docs/HTML](https://developer.mozilla.org/fi/docs/HTML) → [/fi/docs/conflicting/Web/HTML](/fi/docs/conflicting/Web/HTML)

### Renamed
* [/fi/docs/DOM/navigator.doNotTrack](https://developer.mozilla.org/fi/docs/DOM/navigator.doNotTrack) → [/fi/docs/Web/API/Navigator/doNotTrack](/fi/docs/Web/API/Navigator/doNotTrack)
* [/fi/docs/DOM/window.navigator.appCodeName](https://developer.mozilla.org/fi/docs/DOM/window.navigator.appCodeName) → [/fi/docs/Web/API/NavigatorID/appCodeName](/fi/docs/Web/API/NavigatorID/appCodeName)
* [/fi/docs/DOM/window.navigator.appName](https://developer.mozilla.org/fi/docs/DOM/window.navigator.appName) → [/fi/docs/Web/API/NavigatorID/appName](/fi/docs/Web/API/NavigatorID/appName)
* [/fi/docs/DOM/window.navigator.appVersion](https://developer.mozilla.org/fi/docs/DOM/window.navigator.appVersion) → [/fi/docs/Web/API/NavigatorID/appVersion](/fi/docs/Web/API/NavigatorID/appVersion)
* [/fi/docs/DOM/window.navigator.battery](https://developer.mozilla.org/fi/docs/DOM/window.navigator.battery) → [/fi/docs/Web/API/Navigator/battery](/fi/docs/Web/API/Navigator/battery)
* [/fi/docs/DOM/window.navigator.buildID](https://developer.mozilla.org/fi/docs/DOM/window.navigator.buildID) → [/fi/docs/Web/API/Navigator/buildID](/fi/docs/Web/API/Navigator/buildID)
* [/fi/docs/DOM/window.navigator.connection](https://developer.mozilla.org/fi/docs/DOM/window.navigator.connection) → [/fi/docs/Web/API/Navigator/connection](/fi/docs/Web/API/Navigator/connection)
* [/fi/docs/DOM/window.navigator.cookieEnabled](https://developer.mozilla.org/fi/docs/DOM/window.navigator.cookieEnabled) → [/fi/docs/Web/API/Navigator/cookieEnabled](/fi/docs/Web/API/Navigator/cookieEnabled)
* [/fi/docs/DOM/window.navigator.language](https://developer.mozilla.org/fi/docs/DOM/window.navigator.language) → [/fi/docs/Web/API/NavigatorLanguage/language](/fi/docs/Web/API/NavigatorLanguage/language)
* [/fi/docs/DOM/window.navigator.mimeTypes](https://developer.mozilla.org/fi/docs/DOM/window.navigator.mimeTypes) → [/fi/docs/Web/API/NavigatorPlugins/mimeTypes](/fi/docs/Web/API/NavigatorPlugins/mimeTypes)
* [/fi/docs/DOM/window.navigator.onLine](https://developer.mozilla.org/fi/docs/DOM/window.navigator.onLine) → [/fi/docs/Web/API/NavigatorOnLine/onLine](/fi/docs/Web/API/NavigatorOnLine/onLine)
* [/fi/docs/DOM/window.navigator.oscpu](https://developer.mozilla.org/fi/docs/DOM/window.navigator.oscpu) → [/fi/docs/Web/API/Navigator/oscpu](/fi/docs/Web/API/Navigator/oscpu)
* [/fi/docs/DOM/window.navigator.platform](https://developer.mozilla.org/fi/docs/DOM/window.navigator.platform) → [/fi/docs/Web/API/NavigatorID/platform](/fi/docs/Web/API/NavigatorID/platform)
* [/fi/docs/DOM/window.navigator.plugins](https://developer.mozilla.org/fi/docs/DOM/window.navigator.plugins) → [/fi/docs/Web/API/NavigatorPlugins/plugins](/fi/docs/Web/API/NavigatorPlugins/plugins)
* [/fi/docs/DOM/window.navigator.product](https://developer.mozilla.org/fi/docs/DOM/window.navigator.product) → [/fi/docs/Web/API/NavigatorID/product](/fi/docs/Web/API/NavigatorID/product)
* [/fi/docs/DOM/window.navigator.productSub](https://developer.mozilla.org/fi/docs/DOM/window.navigator.productSub) → [/fi/docs/Web/API/Navigator/productSub](/fi/docs/Web/API/Navigator/productSub)
* [/fi/docs/DOM/window.navigator.userAgent](https://developer.mozilla.org/fi/docs/DOM/window.navigator.userAgent) → [/fi/docs/Web/API/NavigatorID/userAgent](/fi/docs/Web/API/NavigatorID/userAgent)
* [/fi/docs/DOM/window.navigator.vendor](https://developer.mozilla.org/fi/docs/DOM/window.navigator.vendor) → [/fi/docs/Web/API/Navigator/vendor](/fi/docs/Web/API/Navigator/vendor)
* [/fi/docs/DOM/window.navigator](https://developer.mozilla.org/fi/docs/DOM/window.navigator) → [/fi/docs/Web/API/Window/navigator](/fi/docs/Web/API/Window/navigator)
* [/fi/docs/HTML/Canvas](https://developer.mozilla.org/fi/docs/HTML/Canvas) → [/fi/docs/Web/API/Canvas_API](/fi/docs/Web/API/Canvas_API)
* [/fi/docs/Learn/JavaScript/Ensimmaiset_askeleet](https://developer.mozilla.org/fi/docs/Learn/JavaScript/Ensimmaiset_askeleet) → [/fi/docs/Learn/JavaScript/First_steps](/fi/docs/Learn/JavaScript/First_steps)
* [/fi/docs/DOM](https://developer.mozilla.org/fi/docs/DOM) → [/fi/docs/Web/API/Document_Object_Model](/fi/docs/Web/API/Document_Object_Model)
