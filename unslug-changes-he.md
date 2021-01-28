# he

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 171 documents.
* Moved 17 document.
  * 6 orphaned documents.
  * 1 conflicting documents.
  * 10 renamed documents.

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

* [/he/docs/he](https://developer.mozilla.org/he/docs/he) → [/he/docs/orphaned/he](/he/docs/orphaned/he)
* [/he/docs/Hebrew_Localization](https://developer.mozilla.org/he/docs/Hebrew_Localization) → [/he/docs/orphaned/Hebrew_Localization](/he/docs/orphaned/Hebrew_Localization)
* [/he/docs/MDN/Community](https://developer.mozilla.org/he/docs/MDN/Community) → [/he/docs/orphaned/MDN/Community](/he/docs/orphaned/MDN/Community)
* [/he/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/he/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/he/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/he/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/he/docs/Web/Hypertext_Markup_Language](https://developer.mozilla.org/he/docs/Web/Hypertext_Markup_Language) → [/he/docs/orphaned/Web/Hypertext_Markup_Language](/he/docs/orphaned/Web/Hypertext_Markup_Language)
* [/he/docs/מושגים](https://developer.mozilla.org/he/docs/מושגים) → [/he/docs/orphaned/מושגים](/he/docs/orphaned/מושגים)

### Conflicting
* [/he/docs/Web_Development](https://developer.mozilla.org/he/docs/Web_Development) → [/he/docs/conflicting/Web/Guide](/he/docs/conflicting/Web/Guide)

### Renamed
* [/he/docs/DOM](https://developer.mozilla.org/he/docs/DOM) → [/he/docs/Web/API/Document_Object_Model](/he/docs/Web/API/Document_Object_Model)
* [/he/docs/Glossary/מערך](https://developer.mozilla.org/he/docs/Glossary/מערך) → [/he/docs/Glossary/array](/he/docs/Glossary/array)
* [/he/docs/Learn/HTML/טבלאות](https://developer.mozilla.org/he/docs/Learn/HTML/טבלאות) → [/he/docs/Learn/HTML/Tables](/he/docs/Learn/HTML/Tables)
* [/he/docs/Learn/HTML/טפסים](https://developer.mozilla.org/he/docs/Learn/HTML/טפסים) → [/he/docs/Learn/Forms](/he/docs/Learn/Forms)
* [/he/docs/Learn/HTML/מבוא_לשפת_HTML](https://developer.mozilla.org/he/docs/Learn/HTML/מבוא_לשפת_HTML) → [/he/docs/Learn/HTML/Introduction_to_HTML](/he/docs/Learn/HTML/Introduction_to_HTML)
* [/he/docs/Learn/HTML/פתרון_בעיות](https://developer.mozilla.org/he/docs/Learn/HTML/פתרון_בעיות) → [/he/docs/Learn/HTML/Howto](/he/docs/Learn/HTML/Howto)
* [/he/docs/Learn/JavaScript/Building_blocks/תנאים](https://developer.mozilla.org/he/docs/Learn/JavaScript/Building_blocks/תנאים) → [/he/docs/Learn/JavaScript/Building_blocks/conditionals](/he/docs/Learn/JavaScript/Building_blocks/conditionals)
* [/he/docs/Mozilla/Add-ons/WebExtensions/manifest.json/הרשאות](https://developer.mozilla.org/he/docs/Mozilla/Add-ons/WebExtensions/manifest.json/הרשאות) → [/he/docs/Mozilla/Add-ons/WebExtensions/manifest.json/permissions](/he/docs/Mozilla/Add-ons/WebExtensions/manifest.json/permissions)
* [/he/docs/Mozilla/Add-ons/WebExtensions/טיפום](https://developer.mozilla.org/he/docs/Mozilla/Add-ons/WebExtensions/טיפום) → [/he/docs/Mozilla/Add-ons/WebExtensions/Tips](/he/docs/Mozilla/Add-ons/WebExtensions/Tips)
* [/he/docs/Web/API/Geolocation/ממשק_שירותי_מיקום](https://developer.mozilla.org/he/docs/Web/API/Geolocation/ממשק_שירותי_מיקום) → [/he/docs/Web/API/Geolocation_API](/he/docs/Web/API/Geolocation_API)
