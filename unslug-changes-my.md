# my

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 21 documents.
* Moved 3 document.
  * 0 orphaned documents.
  * 0 conflicting documents.
  * 3 renamed documents.

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



### Conflicting


### Renamed
* [/my/docs/Learn/HTML/Forms/HTML5_input_types](https://developer.mozilla.org/my/docs/Learn/HTML/Forms/HTML5_input_types) → [/my/docs/Learn/Forms/HTML5_input_types](/my/docs/Learn/Forms/HTML5_input_types)
* [/my/docs/Learn/HTML/Forms](https://developer.mozilla.org/my/docs/Learn/HTML/Forms) → [/my/docs/Learn/Forms](/my/docs/Learn/Forms)
* [/my/docs/Learn/HTML/Forms/Your_first_form](https://developer.mozilla.org/my/docs/Learn/HTML/Forms/Your_first_form) → [/my/docs/Learn/Forms/Your_first_form](/my/docs/Learn/Forms/Your_first_form)
