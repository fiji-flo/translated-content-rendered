# hi-in

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 28 documents.
* Moved 8 document.
  * 3 orphaned documents.
  * 0 conflicting documents.
  * 5 renamed documents.

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

* [/hi-in/docs/MDN/Community](https://developer.mozilla.org/hi-in/docs/MDN/Community) → [/hi-in/docs/orphaned/MDN/Community](/hi-in/docs/orphaned/MDN/Community)
* [/hi-in/docs/MDN/Contribute/Howto/Do_a_technical_review](https://developer.mozilla.org/hi-in/docs/MDN/Contribute/Howto/Do_a_technical_review) → [/hi-in/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review](/hi-in/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review)
* [/hi-in/docs/Web/Localization](https://developer.mozilla.org/hi-in/docs/Web/Localization) → [/hi-in/docs/orphaned/Web/Localization](/hi-in/docs/orphaned/Web/Localization)

### Conflicting


### Renamed
* [/hi-in/docs/Glossary/इंटरनेट](https://developer.mozilla.org/hi-in/docs/Glossary/इंटरनेट) → [/hi-in/docs/Glossary/Internet](/hi-in/docs/Glossary/Internet)
* [/hi-in/docs/Glossary/डेटा_संरचना](https://developer.mozilla.org/hi-in/docs/Glossary/डेटा_संरचना) → [/hi-in/docs/Glossary/Data_structure](/hi-in/docs/Glossary/Data_structure)
* [/hi-in/docs/Glossary/लोकल](https://developer.mozilla.org/hi-in/docs/Glossary/लोकल) → [/hi-in/docs/Glossary/Locale](/hi-in/docs/Glossary/Locale)
* [/hi-in/docs/Web/JavaScript/Reference/Operators/ऑपरेटर_प्राथमिकता](https://developer.mozilla.org/hi-in/docs/Web/JavaScript/Reference/Operators/ऑपरेटर_प्राथमिकता) → [/hi-in/docs/Web/JavaScript/Reference/Operators/Operator_Precedence](/hi-in/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)
* [/hi-in/docs/Web/JavaScript/टाईप्ड_सरणियाँ](https://developer.mozilla.org/hi-in/docs/Web/JavaScript/टाईप्ड_सरणियाँ) → [/hi-in/docs/Web/JavaScript/Typed_arrays](/hi-in/docs/Web/JavaScript/Typed_arrays)
