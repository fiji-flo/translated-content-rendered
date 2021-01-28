# hu

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 79 documents.
* Moved 23 document.
  * 0 orphaned documents.
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



### Conflicting
* [/hu/docs/DOM](https://developer.mozilla.org/hu/docs/DOM) → [/hu/docs/conflicting/Web/API/Document_Object_Model](/hu/docs/conflicting/Web/API/Document_Object_Model)

### Renamed
* [/hu/docs/CSS/CSS_Grid_Layout](https://developer.mozilla.org/hu/docs/CSS/CSS_Grid_Layout) → [/hu/docs/Web/CSS/CSS_Grid_Layout](/hu/docs/Web/CSS/CSS_Grid_Layout)
* [/hu/docs/CSS/font-weight](https://developer.mozilla.org/hu/docs/CSS/font-weight) → [/hu/docs/Web/CSS/font-weight](/hu/docs/Web/CSS/font-weight)
* [/hu/docs/CSS](https://developer.mozilla.org/hu/docs/CSS) → [/hu/docs/Web/CSS](/hu/docs/Web/CSS)
* [/hu/docs/CSS/text-decoration](https://developer.mozilla.org/hu/docs/CSS/text-decoration) → [/hu/docs/Web/CSS/text-decoration](/hu/docs/Web/CSS/text-decoration)
* [/hu/docs/DOM/HTMLBRElement](https://developer.mozilla.org/hu/docs/DOM/HTMLBRElement) → [/hu/docs/Web/API/HTMLBRElement](/hu/docs/Web/API/HTMLBRElement)
* [/hu/docs/Glossary/bongeszo](https://developer.mozilla.org/hu/docs/Glossary/bongeszo) → [/hu/docs/Glossary/Browser](/hu/docs/Glossary/Browser)
* [/hu/docs/Glossary/Elso_osztalyu_funkciok](https://developer.mozilla.org/hu/docs/Glossary/Elso_osztalyu_funkciok) → [/hu/docs/Glossary/First-class_Function](/hu/docs/Glossary/First-class_Function)
* [/hu/docs/Learn/HTML/Bevezetes_a_HTML-be](https://developer.mozilla.org/hu/docs/Learn/HTML/Bevezetes_a_HTML-be) → [/hu/docs/Learn/HTML/Introduction_to_HTML](/hu/docs/Learn/HTML/Introduction_to_HTML)
* [/hu/docs/Learn/Ismerkedés_a_Világhálóval/Alapvető_programok_telepítése](https://developer.mozilla.org/hu/docs/Learn/Ismerkedés_a_Világhálóval/Alapvető_programok_telepítése) → [/hu/docs/Learn/Getting_started_with_the_web/Installing_basic_software](/hu/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/hu/docs/Learn/Ismerkedés_a_Világhálóval/Hogy_fog_kinézni_a_weboldalunk](https://developer.mozilla.org/hu/docs/Learn/Ismerkedés_a_Világhálóval/Hogy_fog_kinézni_a_weboldalunk) → [/hu/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like](/hu/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
* [/hu/docs/Learn/Ismerkedés_a_Világhálóval](https://developer.mozilla.org/hu/docs/Learn/Ismerkedés_a_Világhálóval) → [/hu/docs/Learn/Getting_started_with_the_web](/hu/docs/Learn/Getting_started_with_the_web)
* [/hu/docs/Learn/JavaScript/Első_lépések](https://developer.mozilla.org/hu/docs/Learn/JavaScript/Első_lépések) → [/hu/docs/Learn/JavaScript/First_steps](/hu/docs/Learn/JavaScript/First_steps)
* [/hu/docs/Web/API/Window.stop](https://developer.mozilla.org/hu/docs/Web/API/Window.stop) → [/hu/docs/Web/API/Window/stop](/hu/docs/Web/API/Window/stop)
* [/hu/docs/Web/API/XMLHttpRequest/XMLHttpRequest_hasznalata](https://developer.mozilla.org/hu/docs/Web/API/XMLHttpRequest/XMLHttpRequest_hasznalata) → [/hu/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest](/hu/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest)
* [/hu/docs/Web/CSS/Tools/Border-radius_bemutato](https://developer.mozilla.org/hu/docs/Web/CSS/Tools/Border-radius_bemutato) → [/hu/docs/Web/CSS/CSS_Background_and_Borders/Border-radius_generator](/hu/docs/Web/CSS/CSS_Background_and_Borders/Border-radius_generator)
* [/hu/docs/Web/Guide/Grafika](https://developer.mozilla.org/hu/docs/Web/Guide/Grafika) → [/hu/docs/Web/Guide/Graphics](/hu/docs/Web/Guide/Graphics)
* [/hu/docs/Web/JavaScript/a_javascript_ujboli_bemutatasa](https://developer.mozilla.org/hu/docs/Web/JavaScript/a_javascript_ujboli_bemutatasa) → [/hu/docs/Web/JavaScript/A_re-introduction_to_JavaScript](/hu/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
* [/hu/docs/Web/JavaScript/Guide/Bevezetés](https://developer.mozilla.org/hu/docs/Web/JavaScript/Guide/Bevezetés) → [/hu/docs/Web/JavaScript/Guide/Introduction](/hu/docs/Web/JavaScript/Guide/Introduction)
* [/hu/docs/Web/JavaScript/Reference/Errors/Érvénytelen_típus](https://developer.mozilla.org/hu/docs/Web/JavaScript/Reference/Errors/Érvénytelen_típus) → [/hu/docs/Web/JavaScript/Reference/Errors/Unexpected_type](/hu/docs/Web/JavaScript/Reference/Errors/Unexpected_type)
* [/hu/docs/Web/JavaScript/Reference/Global_Objects/Függvény](https://developer.mozilla.org/hu/docs/Web/JavaScript/Reference/Global_Objects/Függvény) → [/hu/docs/Web/JavaScript/Reference/Global_Objects/Function](/hu/docs/Web/JavaScript/Reference/Global_Objects/Function)
* [/hu/docs/WebSockets](https://developer.mozilla.org/hu/docs/WebSockets) → [/hu/docs/Web/API/WebSockets_API](/hu/docs/Web/API/WebSockets_API)
* [/hu/docs/Bevezetés_a_dokumentumobjektum-modellbe](https://developer.mozilla.org/hu/docs/Bevezetés_a_dokumentumobjektum-modellbe) → [/hu/docs/Web/API/Document_Object_Model](/hu/docs/Web/API/Document_Object_Model)
