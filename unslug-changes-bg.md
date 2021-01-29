# bg

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 76 documents.
* Moved 22 document.
  * 0 orphaned documents.
  * 1 conflicting documents.
  * 21 renamed documents.

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
* [/bg/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators](https://developer.mozilla.org/bg/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators) → [/bg/docs/conflicting/Web/JavaScript/Reference/Operators](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/conflicting/Web/JavaScript/Reference/Operators)

### Renamed
* [/bg/docs/Learn/Да_започнем_с_Мрежата](https://developer.mozilla.org/bg/docs/Learn/Да_започнем_с_Мрежата) → [/bg/docs/Learn/Getting_started_with_the_web](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Learn/Getting_started_with_the_web)
* [/bg/docs/Learn/Да_започнем_с_Мрежата/Инсталиране_на_основния_софтуер](https://developer.mozilla.org/bg/docs/Learn/Да_започнем_с_Мрежата/Инсталиране_на_основния_софтуер) → [/bg/docs/Learn/Getting_started_with_the_web/Installing_basic_software](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/bg/docs/Learn/Да_започнем_с_Мрежата/Основи_на_HTML](https://developer.mozilla.org/bg/docs/Learn/Да_започнем_с_Мрежата/Основи_на_HTML) → [/bg/docs/Learn/Getting_started_with_the_web/HTML_basics](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Learn/Getting_started_with_the_web/HTML_basics)
* [/bg/docs/MDN/Getting_started](https://developer.mozilla.org/bg/docs/MDN/Getting_started) → [/bg/docs/MDN/Contribute/Getting_started](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/MDN/Contribute/Getting_started)
* [/bg/docs/Web/Guide/Графики](https://developer.mozilla.org/bg/docs/Web/Guide/Графики) → [/bg/docs/Web/Guide/Graphics](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Web/Guide/Graphics)
* [/bg/docs/Web/JavaScript/Reference/Operators/разпределящ_синтаксис](https://developer.mozilla.org/bg/docs/Web/JavaScript/Reference/Operators/разпределящ_синтаксис) → [/bg/docs/Web/JavaScript/Reference/Operators/Spread_syntax](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
* [/bg/docs/Web/SVG/Ръководство](https://developer.mozilla.org/bg/docs/Web/SVG/Ръководство) → [/bg/docs/Web/SVG/Tutorial](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Web/SVG/Tutorial)
* [/bg/docs/Речник/404](https://developer.mozilla.org/bg/docs/Речник/404) → [/bg/docs/Glossary/404](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/404)
* [/bg/docs/Речник/array](https://developer.mozilla.org/bg/docs/Речник/array) → [/bg/docs/Glossary/array](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/array)
* [/bg/docs/Речник/Browser](https://developer.mozilla.org/bg/docs/Речник/Browser) → [/bg/docs/Glossary/Browser](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/Browser)
* [/bg/docs/Речник/CSS](https://developer.mozilla.org/bg/docs/Речник/CSS) → [/bg/docs/Glossary/CSS](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/CSS)
* [/bg/docs/Речник/ECMA](https://developer.mozilla.org/bg/docs/Речник/ECMA) → [/bg/docs/Glossary/ECMA](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/ECMA)
* [/bg/docs/Речник/HTML](https://developer.mozilla.org/bg/docs/Речник/HTML) → [/bg/docs/Glossary/HTML](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/HTML)
* [/bg/docs/Речник/HTTP](https://developer.mozilla.org/bg/docs/Речник/HTTP) → [/bg/docs/Glossary/HTTP](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/HTTP)
* [/bg/docs/Речник/Hypertext](https://developer.mozilla.org/bg/docs/Речник/Hypertext) → [/bg/docs/Glossary/Hypertext](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/Hypertext)
* [/bg/docs/Речник](https://developer.mozilla.org/bg/docs/Речник) → [/bg/docs/Glossary](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary)
* [/bg/docs/Речник/Internet](https://developer.mozilla.org/bg/docs/Речник/Internet) → [/bg/docs/Glossary/Internet](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/Internet)
* [/bg/docs/Речник/JavaScript](https://developer.mozilla.org/bg/docs/Речник/JavaScript) → [/bg/docs/Glossary/JavaScript](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/JavaScript)
* [/bg/docs/Речник/JSON](https://developer.mozilla.org/bg/docs/Речник/JSON) → [/bg/docs/Glossary/JSON](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/JSON)
* [/bg/docs/Речник/Server](https://developer.mozilla.org/bg/docs/Речник/Server) → [/bg/docs/Glossary/Server](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/Server)
* [/bg/docs/Речник/World_Wide_Web](https://developer.mozilla.org/bg/docs/Речник/World_Wide_Web) → [/bg/docs/Glossary/World_Wide_Web](https://unslug-next.content.dev.mdn.mozit.cloud/bg/docs/Glossary/World_Wide_Web)
