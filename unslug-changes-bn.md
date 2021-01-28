# bn

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 124 documents.
* Moved 34 document.
  * 3 orphaned documents.
  * 4 conflicting documents.
  * 27 renamed documents.

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

* [/bn/docs/MDN/Community](https://developer.mozilla.org/bn/docs/MDN/Community) → [/bn/docs/orphaned/MDN/Community](/bn/docs/orphaned/MDN/Community)
* [/bn/docs/MDN/Community/Whats_happening](https://developer.mozilla.org/bn/docs/MDN/Community/Whats_happening) → [/bn/docs/orphaned/MDN/Community/Whats_happening](/bn/docs/orphaned/MDN/Community/Whats_happening)
* [/bn/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/bn/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/bn/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/bn/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)

### Conflicting
* [/bn/docs/Web_Development](https://developer.mozilla.org/bn/docs/Web_Development) → [/bn/docs/conflicting/Web/Guide](/bn/docs/conflicting/Web/Guide)
* [/bn/docs/Web/CSS/Getting_Started/Why_use_CSS](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/Why_use_CSS) → [/bn/docs/conflicting/Learn/CSS/First_steps/How_CSS_works](/bn/docs/conflicting/Learn/CSS/First_steps/How_CSS_works)
* [/bn/docs/Web/Guide/API/DOM](https://developer.mozilla.org/bn/docs/Web/Guide/API/DOM) → [/bn/docs/conflicting/Web/API/Document_Object_Model](/bn/docs/conflicting/Web/API/Document_Object_Model)
* [/bn/docs/Web/HTML/Canvas/Tutorial](https://developer.mozilla.org/bn/docs/Web/HTML/Canvas/Tutorial) → [/bn/docs/conflicting/Web/API/Canvas_API/Tutorial](/bn/docs/conflicting/Web/API/Canvas_API/Tutorial)

### Renamed
* [/bn/docs/HTML/HTML5](https://developer.mozilla.org/bn/docs/HTML/HTML5) → [/bn/docs/Web/Guide/HTML/HTML5](/bn/docs/Web/Guide/HTML/HTML5)
* [/bn/docs/HTML/HTML5/Introduction_to_HTML5](https://developer.mozilla.org/bn/docs/HTML/HTML5/Introduction_to_HTML5) → [/bn/docs/Web/Guide/HTML/HTML5/Introduction_to_HTML5](/bn/docs/Web/Guide/HTML/HTML5/Introduction_to_HTML5)
* [/bn/docs/Learn/JavaScript/First_steps/জাভাস্ক্রিপ্ট-কী](https://developer.mozilla.org/bn/docs/Learn/JavaScript/First_steps/জাভাস্ক্রিপ্ট-কী) → [/bn/docs/Learn/JavaScript/First_steps/What_is_JavaScript](/bn/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
* [/bn/docs/Localization](https://developer.mozilla.org/bn/docs/Localization) → [/bn/docs/Glossary/Localization](/bn/docs/Glossary/Localization)
* [/bn/docs/MDN_at_ten](https://developer.mozilla.org/bn/docs/MDN_at_ten) → [/bn/docs/MDN/At_ten](/bn/docs/MDN/At_ten)
* [/bn/docs/MDN/Contribute/Creating_and_editing_pages](https://developer.mozilla.org/bn/docs/MDN/Contribute/Creating_and_editing_pages) → [/bn/docs/MDN/Contribute/Howto/Create_and_edit_pages](/bn/docs/MDN/Contribute/Howto/Create_and_edit_pages)
* [/bn/docs/MDN/Guidelines/Style_guide](https://developer.mozilla.org/bn/docs/MDN/Guidelines/Style_guide) → [/bn/docs/MDN/Guidelines/Writing_style_guide](/bn/docs/MDN/Guidelines/Writing_style_guide)
* [/bn/docs/Mozilla/ফায়ারফক্স](https://developer.mozilla.org/bn/docs/Mozilla/ফায়ারফক্স) → [/bn/docs/Mozilla/Firefox](/bn/docs/Mozilla/Firefox)
* [/bn/docs/Mozilla/ফায়ারফক্স/রিলিজস](https://developer.mozilla.org/bn/docs/Mozilla/ফায়ারফক্স/রিলিজস) → [/bn/docs/Mozilla/Firefox/Releases](/bn/docs/Mozilla/Firefox/Releases)
* [/bn/docs/Tools/ত্রিমাত্রিক_দর্শন](https://developer.mozilla.org/bn/docs/Tools/ত্রিমাত্রিক_দর্শন) → [/bn/docs/Tools/3D_View](/bn/docs/Tools/3D_View)
* [/bn/docs/Web/Guide/HTML/Canvas_tutorial](https://developer.mozilla.org/bn/docs/Web/Guide/HTML/Canvas_tutorial) → [/bn/docs/Web/API/Canvas_API/Tutorial](/bn/docs/Web/API/Canvas_API/Tutorial)
* [/bn/docs/Web/Guide/HTML/Content_Editable](https://developer.mozilla.org/bn/docs/Web/Guide/HTML/Content_Editable) → [/bn/docs/Web/Guide/HTML/Editable_content](/bn/docs/Web/Guide/HTML/Editable_content)
* [/bn/docs/Web/Guide/HTML/Forms](https://developer.mozilla.org/bn/docs/Web/Guide/HTML/Forms) → [/bn/docs/Learn/Forms](/bn/docs/Learn/Forms)
* [/bn/docs/Web/Guide/গ্রাফিক্স](https://developer.mozilla.org/bn/docs/Web/Guide/গ্রাফিক্স) → [/bn/docs/Web/Guide/Graphics](/bn/docs/Web/Guide/Graphics)
* [/bn/docs/Web/HTML/Canvas](https://developer.mozilla.org/bn/docs/Web/HTML/Canvas) → [/bn/docs/Web/API/Canvas_API](/bn/docs/Web/API/Canvas_API)
* [/bn/docs/Web/HTML/CORS_settings_attributes](https://developer.mozilla.org/bn/docs/Web/HTML/CORS_settings_attributes) → [/bn/docs/Web/HTML/Attributes/crossorigin](/bn/docs/Web/HTML/Attributes/crossorigin)
* [/bn/docs/Web/JavaScript/ভাষার_রিসোর্স](https://developer.mozilla.org/bn/docs/Web/JavaScript/ভাষার_রিসোর্স) → [/bn/docs/Web/JavaScript/Language_Resources](/bn/docs/Web/JavaScript/Language_Resources)
* [/bn/docs/DOM](https://developer.mozilla.org/bn/docs/DOM) → [/bn/docs/Web/API/Document_Object_Model](/bn/docs/Web/API/Document_Object_Model)
* [/bn/docs/Web/CSS/Getting_Started/Color](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/Color) → [/bn/docs/Learn/CSS/Building_blocks/Values_and_units](/bn/docs/Learn/CSS/Building_blocks/Values_and_units)
* [/bn/docs/Web/CSS/Getting_Started/How_CSS_works](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/How_CSS_works) → [/bn/docs/Learn/CSS/First_steps/How_CSS_works](/bn/docs/Learn/CSS/First_steps/How_CSS_works)
* [/bn/docs/Web/CSS/Getting_Started](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started) → [/bn/docs/Learn/CSS/First_steps](/bn/docs/Learn/CSS/First_steps)
* [/bn/docs/Web/CSS/Getting_Started/Readable_CSS](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/Readable_CSS) → [/bn/docs/Learn/CSS/First_steps/How_CSS_is_structured](/bn/docs/Learn/CSS/First_steps/How_CSS_is_structured)
* [/bn/docs/Web/CSS/Getting_Started/Text_styles](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/Text_styles) → [/bn/docs/Learn/CSS/Styling_text/Fundamentals](/bn/docs/Learn/CSS/Styling_text/Fundamentals)
* [/bn/docs/Web/CSS/Getting_Started/নই](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/নই) → [/bn/docs/Learn/CSS/Building_blocks/Selectors](/bn/docs/Learn/CSS/Building_blocks/Selectors)
* [/bn/docs/Web/CSS/Getting_Started/লে-আউট](https://developer.mozilla.org/bn/docs/Web/CSS/Getting_Started/লে-আউট) → [/bn/docs/Learn/CSS/CSS_layout](/bn/docs/Learn/CSS/CSS_layout)
* [/bn/docs/Web/Guide/API/WebRTC](https://developer.mozilla.org/bn/docs/Web/Guide/API/WebRTC) → [/bn/docs/Web/API/WebRTC_API](/bn/docs/Web/API/WebRTC_API)
* [/bn/docs/Web/HTML/Focus_management_in_HTML](https://developer.mozilla.org/bn/docs/Web/HTML/Focus_management_in_HTML) → [/bn/docs/Web/API/Document/hasFocus](/bn/docs/Web/API/Document/hasFocus)
