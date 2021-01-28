# th

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 62 documents.
* Moved 9 document.
  * 2 orphaned documents.
  * 0 conflicting documents.
  * 7 renamed documents.

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

* [/th/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/th/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/th/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/th/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/th/docs/MDN/Contribute/Howto/Do_a_technical_review](https://developer.mozilla.org/th/docs/MDN/Contribute/Howto/Do_a_technical_review) → [/th/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review](/th/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review)

### Conflicting


### Renamed
* [/th/docs/Learn/ฝั่งเซิร์ฟเวอร์](https://developer.mozilla.org/th/docs/Learn/ฝั่งเซิร์ฟเวอร์) → [/th/docs/Learn/Server-side](/th/docs/Learn/Server-side)
* [/th/docs/Learn/เริ่มต้นใช้งานเว็บ](https://developer.mozilla.org/th/docs/Learn/เริ่มต้นใช้งานเว็บ) → [/th/docs/Learn/Getting_started_with_the_web](/th/docs/Learn/Getting_started_with_the_web)
* [/th/docs/MDN_at_ten](https://developer.mozilla.org/th/docs/MDN_at_ten) → [/th/docs/MDN/At_ten](/th/docs/MDN/At_ten)
* [/th/docs/Mozilla/Firefox/เปิดผนึก/30](https://developer.mozilla.org/th/docs/Mozilla/Firefox/เปิดผนึก/30) → [/th/docs/Mozilla/Firefox/Releases/30](/th/docs/Mozilla/Firefox/Releases/30)
* [/th/docs/Mozilla/Firefox/เปิดผนึก/47](https://developer.mozilla.org/th/docs/Mozilla/Firefox/เปิดผนึก/47) → [/th/docs/Mozilla/Firefox/Releases/47](/th/docs/Mozilla/Firefox/Releases/47)
* [/th/docs/Mozilla/Firefox/เปิดผนึก](https://developer.mozilla.org/th/docs/Mozilla/Firefox/เปิดผนึก) → [/th/docs/Mozilla/Firefox/Releases](/th/docs/Mozilla/Firefox/Releases)
* [/th/docs/Tools/Debugger/www.หนังโป้.com](https://developer.mozilla.org/th/docs/Tools/Debugger/www.หนังโป้.com) → [/th/docs/Tools/Debugger/UI_Tour](/th/docs/Tools/Debugger/UI_Tour)
