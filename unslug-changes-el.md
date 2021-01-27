# el

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 54 documents.
* Moved 14 document.
  * 1 orphaned documents.
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

* [/el/docs/MDN/Contribute/Howto/Dhmiourgia_logariasmou_MDN](https://developer.mozilla.org/el/docs/MDN/Contribute/Howto/Dhmiourgia_logariasmou_MDN) → [/el/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/el/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)

### Conflicting


### Renamed
* [/el/docs/Glossary/Δείκτης](https://developer.mozilla.org/el/docs/Glossary/Δείκτης) → [/el/docs/Glossary/Index](/el/docs/Glossary/Index)
* [/el/docs/Glossary/Προσβασιμότητα](https://developer.mozilla.org/el/docs/Glossary/Προσβασιμότητα) → [/el/docs/Glossary/Accessibility](/el/docs/Glossary/Accessibility)
* [/el/docs/Learn/Common_questions/Πώς_δουλεύει_το_Διαδίκτυο](https://developer.mozilla.org/el/docs/Learn/Common_questions/Πώς_δουλεύει_το_Διαδίκτυο) → [/el/docs/Learn/Common_questions/How_does_the_Internet_work](/el/docs/Learn/Common_questions/How_does_the_Internet_work)
* [/el/docs/Learn/Common_questions/Σελίδες_τόποι_διακομιστές_και_μηχανές_αναζήτησης](https://developer.mozilla.org/el/docs/Learn/Common_questions/Σελίδες_τόποι_διακομιστές_και_μηχανές_αναζήτησης) → [/el/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines](/el/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines)
* [/el/docs/Learn/Common_questions/Τι_είναι_οι_υπερσύνδεσμοι](https://developer.mozilla.org/el/docs/Learn/Common_questions/Τι_είναι_οι_υπερσύνδεσμοι) → [/el/docs/Learn/Common_questions/What_are_hyperlinks](/el/docs/Learn/Common_questions/What_are_hyperlinks)
* [/el/docs/Learn/HTML/Forms](https://developer.mozilla.org/el/docs/Learn/HTML/Forms) → [/el/docs/Learn/Forms](/el/docs/Learn/Forms)
* [/el/docs/Learn/HTML/Forms/Επικύρωση_δεδομένων_φόρμας](https://developer.mozilla.org/el/docs/Learn/HTML/Forms/Επικύρωση_δεδομένων_φόρμας) → [/el/docs/Learn/Forms/Form_validation](/el/docs/Learn/Forms/Form_validation)
* [/el/docs/Learn/JavaScript/Πρώτα_βήματα](https://developer.mozilla.org/el/docs/Learn/JavaScript/Πρώτα_βήματα) → [/el/docs/Learn/JavaScript/First_steps](/el/docs/Learn/JavaScript/First_steps)
* [/el/docs/MDN_at_ten](https://developer.mozilla.org/el/docs/MDN_at_ten) → [/el/docs/MDN/At_ten](/el/docs/MDN/At_ten)
* [/el/docs/Mozilla/Πρόσθετα](https://developer.mozilla.org/el/docs/Mozilla/Πρόσθετα) → [/el/docs/Mozilla/Add-ons](/el/docs/Mozilla/Add-ons)
* [/el/docs/Web/JavaScript/Reference/Functions/Προεπιλεγμένες_παράμετροι](https://developer.mozilla.org/el/docs/Web/JavaScript/Reference/Functions/Προεπιλεγμένες_παράμετροι) → [/el/docs/Web/JavaScript/Reference/Functions/Default_parameters](/el/docs/Web/JavaScript/Reference/Functions/Default_parameters)
* [/el/docs/Εργαλεία/about:debugging](https://developer.mozilla.org/el/docs/Εργαλεία/about:debugging) → [/el/docs/Tools/about:debugging](/el/docs/Tools/about:debugging)
* [/el/docs/Εργαλεία](https://developer.mozilla.org/el/docs/Εργαλεία) → [/el/docs/Tools](/el/docs/Tools)
