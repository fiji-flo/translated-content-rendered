# kab

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 61 documents.
* Moved 13 document.
  * 4 orphaned documents.
  * 0 conflicting documents.
  * 9 renamed documents.

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

* [/kab/docs/Games/Tools/Engines_and_tools](https://developer.mozilla.org/kab/docs/Games/Tools/Engines_and_tools) → [/kab/docs/orphaned/Games/Tools/Engines_and_tools](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/orphaned/Games/Tools/Engines_and_tools)
* [/kab/docs/Glossary/aneggaf](https://developer.mozilla.org/kab/docs/Glossary/aneggaf) → [/kab/docs/orphaned/Glossary/aneggaf](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/orphaned/Glossary/aneggaf)
* [/kab/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/kab/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/kab/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/kab/docs/MDN/Tamezdaynutt](https://developer.mozilla.org/kab/docs/MDN/Tamezdaynutt) → [/kab/docs/orphaned/MDN/Community](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/orphaned/MDN/Community)

### Conflicting


### Renamed
* [/kab/docs/Games/Imedyaten](https://developer.mozilla.org/kab/docs/Games/Imedyaten) → [/kab/docs/Games/Examples](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Games/Examples)
* [/kab/docs/Lmed/Getting_started_with_the_web/HTML_basics](https://developer.mozilla.org/kab/docs/Lmed/Getting_started_with_the_web/HTML_basics) → [/kab/docs/Learn/Getting_started_with_the_web/HTML_basics](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Learn/Getting_started_with_the_web/HTML_basics)
* [/kab/docs/Lmed/Getting_started_with_the_web](https://developer.mozilla.org/kab/docs/Lmed/Getting_started_with_the_web) → [/kab/docs/Learn/Getting_started_with_the_web](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Learn/Getting_started_with_the_web)
* [/kab/docs/Lmed/HTML](https://developer.mozilla.org/kab/docs/Lmed/HTML) → [/kab/docs/Learn/HTML](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Learn/HTML)
* [/kab/docs/Lmed/HTML/Introduction_to_HTML](https://developer.mozilla.org/kab/docs/Lmed/HTML/Introduction_to_HTML) → [/kab/docs/Learn/HTML/Introduction_to_HTML](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Learn/HTML/Introduction_to_HTML)
* [/kab/docs/Lmed](https://developer.mozilla.org/kab/docs/Lmed) → [/kab/docs/Learn](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Learn)
* [/kab/docs/Tools/Tadiwent_Web](https://developer.mozilla.org/kab/docs/Tools/Tadiwent_Web) → [/kab/docs/Tools/Web_Console](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Tools/Web_Console)
* [/kab/docs/Web/JavaScript/Amnir](https://developer.mozilla.org/kab/docs/Web/JavaScript/Amnir) → [/kab/docs/Web/JavaScript/Guide](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Web/JavaScript/Guide)
* [/kab/docs/Web/Tuffart](https://developer.mozilla.org/kab/docs/Web/Tuffart) → [/kab/docs/Web/Accessibility](https://unslugged.content.dev.mdn.mozit.cloud/kab/docs/Web/Accessibility)
