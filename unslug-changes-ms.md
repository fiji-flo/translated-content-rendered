# ms

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 30 documents.
* Moved 15 document.
  * 2 orphaned documents.
  * 0 conflicting documents.
  * 13 renamed documents.

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

* [/ms/docs/MDN/Community](https://developer.mozilla.org/ms/docs/MDN/Community) → [/ms/docs/orphaned/MDN/Community](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/orphaned/MDN/Community)
* [/ms/docs/MDN/Contribute/Howto/Bagaimana_membuat_akaun_MDN](https://developer.mozilla.org/ms/docs/MDN/Contribute/Howto/Bagaimana_membuat_akaun_MDN) → [/ms/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)

### Conflicting


### Renamed
* [/ms/docs/HTML/Canvas](https://developer.mozilla.org/ms/docs/HTML/Canvas) → [/ms/docs/Web/API/Canvas_API](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Web/API/Canvas_API)
* [/ms/docs/HTML/Canvas/Melukis_Grafik_dengan_Canvas](https://developer.mozilla.org/ms/docs/HTML/Canvas/Melukis_Grafik_dengan_Canvas) → [/ms/docs/Web/API/Canvas_API/Tutorial](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Web/API/Canvas_API/Tutorial)
* [/ms/docs/HTML/Elemen](https://developer.mozilla.org/ms/docs/HTML/Elemen) → [/ms/docs/Web/HTML/Element](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Web/HTML/Element)
* [/ms/docs/HTML](https://developer.mozilla.org/ms/docs/HTML) → [/ms/docs/Web/HTML](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Web/HTML)
* [/ms/docs/HTML/Tip_menulis_LamanHTML_dengan_pemuatan_pantas](https://developer.mozilla.org/ms/docs/HTML/Tip_menulis_LamanHTML_dengan_pemuatan_pantas) → [/ms/docs/Learn/HTML/Howto/Author_fast-loading_HTML_pages](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/HTML/Howto/Author_fast-loading_HTML_pages)
* [/ms/docs/Learn/HTML/Forms](https://developer.mozilla.org/ms/docs/Learn/HTML/Forms) → [/ms/docs/Learn/Forms](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/Forms)
* [/ms/docs/Learn/HTML/Howto/Add_responsive_image_to_a_webpage](https://developer.mozilla.org/ms/docs/Learn/HTML/Howto/Add_responsive_image_to_a_webpage) → [/ms/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
* [/ms/docs/Learn/Memulakan_pembelajaran_web/Berurusan_dengan_fail](https://developer.mozilla.org/ms/docs/Learn/Memulakan_pembelajaran_web/Berurusan_dengan_fail) → [/ms/docs/Learn/Getting_started_with_the_web/Dealing_with_files](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/Getting_started_with_the_web/Dealing_with_files)
* [/ms/docs/Learn/Memulakan_pembelajaran_web](https://developer.mozilla.org/ms/docs/Learn/Memulakan_pembelajaran_web) → [/ms/docs/Learn/Getting_started_with_the_web](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/Getting_started_with_the_web)
* [/ms/docs/Learn/Memulakan_pembelajaran_web/Memasang_Perisian_Asas](https://developer.mozilla.org/ms/docs/Learn/Memulakan_pembelajaran_web/Memasang_Perisian_Asas) → [/ms/docs/Learn/Getting_started_with_the_web/Installing_basic_software](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/ms/docs/Learn/Soalan_lazim](https://developer.mozilla.org/ms/docs/Learn/Soalan_lazim) → [/ms/docs/Learn/Common_questions](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Learn/Common_questions)
* [/ms/docs/MDN_at_ten](https://developer.mozilla.org/ms/docs/MDN_at_ten) → [/ms/docs/MDN/At_ten](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/MDN/At_ten)
* [/ms/docs/Web_Development](https://developer.mozilla.org/ms/docs/Web_Development) → [/ms/docs/Web/Guide](https://unslugged.content.dev.mdn.mozit.cloud/ms/docs/Web/Guide)
