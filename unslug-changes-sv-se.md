# sv-se

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 42 documents.
* Moved 10 document.
  * 2 orphaned documents.
  * 1 conflicting documents.
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

* [/sv-SE/docs/MDN/Community](https://developer.mozilla.org/sv-SE/docs/MDN/Community) → [/sv-SE/docs/orphaned/MDN/Community](/sv-SE/docs/orphaned/MDN/Community)
* [/sv-SE/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/sv-SE/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/sv-SE/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/sv-SE/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)

### Conflicting
* [/sv-SE/docs/Web/API/KryptoNyckel/typ](https://developer.mozilla.org/sv-SE/docs/Web/API/KryptoNyckel/typ) → [/sv-SE/docs/conflicting/Web/API/CryptoKey](/sv-SE/docs/conflicting/Web/API/CryptoKey)

### Renamed
* [/sv-SE/docs/Glossary/IP_Adress](https://developer.mozilla.org/sv-SE/docs/Glossary/IP_Adress) → [/sv-SE/docs/Glossary/IP_Address](/sv-SE/docs/Glossary/IP_Address)
* [/sv-SE/docs/Tools/Prestanda](https://developer.mozilla.org/sv-SE/docs/Tools/Prestanda) → [/sv-SE/docs/Tools/Performance](/sv-SE/docs/Tools/Performance)
* [/sv-SE/docs/Web/API/KryptoNyckel](https://developer.mozilla.org/sv-SE/docs/Web/API/KryptoNyckel) → [/sv-SE/docs/Web/API/CryptoKey](/sv-SE/docs/Web/API/CryptoKey)
* [/sv-SE/docs/Web/API/SubtleCrypto/genereraNyckel](https://developer.mozilla.org/sv-SE/docs/Web/API/SubtleCrypto/genereraNyckel) → [/sv-SE/docs/Web/API/SubtleCrypto/generateKey](/sv-SE/docs/Web/API/SubtleCrypto/generateKey)
* [/sv-SE/docs/Web/API/SubtleCrypto/signum](https://developer.mozilla.org/sv-SE/docs/Web/API/SubtleCrypto/signum) → [/sv-SE/docs/Web/API/SubtleCrypto/sign](/sv-SE/docs/Web/API/SubtleCrypto/sign)
* [/sv-SE/docs/Web/HTML/Global_attributes/Kortplats](https://developer.mozilla.org/sv-SE/docs/Web/HTML/Global_attributes/Kortplats) → [/sv-SE/docs/Web/HTML/Global_attributes/slot](/sv-SE/docs/Web/HTML/Global_attributes/slot)
* [/sv-SE/docs/Web/Security/Osäkra_lösenord](https://developer.mozilla.org/sv-SE/docs/Web/Security/Osäkra_lösenord) → [/sv-SE/docs/Web/Security/Insecure_passwords](/sv-SE/docs/Web/Security/Insecure_passwords)
