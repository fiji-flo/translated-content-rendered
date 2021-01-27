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

* [/sv-se/docs/MDN/Community](https://developer.mozilla.org/sv-se/docs/MDN/Community) → [/sv-se/docs/orphaned/MDN/Community](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/orphaned/MDN/Community)
* [/sv-se/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/sv-se/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/sv-se/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)

### Conflicting
* [/sv-se/docs/Web/API/KryptoNyckel/typ](https://developer.mozilla.org/sv-se/docs/Web/API/KryptoNyckel/typ) → [/sv-se/docs/conflicting/Web/API/CryptoKey](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/conflicting/Web/API/CryptoKey)

### Renamed
* [/sv-se/docs/Glossary/IP_Adress](https://developer.mozilla.org/sv-se/docs/Glossary/IP_Adress) → [/sv-se/docs/Glossary/IP_Address](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Glossary/IP_Address)
* [/sv-se/docs/Tools/Prestanda](https://developer.mozilla.org/sv-se/docs/Tools/Prestanda) → [/sv-se/docs/Tools/Performance](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Tools/Performance)
* [/sv-se/docs/Web/API/KryptoNyckel](https://developer.mozilla.org/sv-se/docs/Web/API/KryptoNyckel) → [/sv-se/docs/Web/API/CryptoKey](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Web/API/CryptoKey)
* [/sv-se/docs/Web/API/SubtleCrypto/genereraNyckel](https://developer.mozilla.org/sv-se/docs/Web/API/SubtleCrypto/genereraNyckel) → [/sv-se/docs/Web/API/SubtleCrypto/generateKey](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Web/API/SubtleCrypto/generateKey)
* [/sv-se/docs/Web/API/SubtleCrypto/signum](https://developer.mozilla.org/sv-se/docs/Web/API/SubtleCrypto/signum) → [/sv-se/docs/Web/API/SubtleCrypto/sign](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Web/API/SubtleCrypto/sign)
* [/sv-se/docs/Web/HTML/Global_attributes/Kortplats](https://developer.mozilla.org/sv-se/docs/Web/HTML/Global_attributes/Kortplats) → [/sv-se/docs/Web/HTML/Global_attributes/slot](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Web/HTML/Global_attributes/slot)
* [/sv-se/docs/Web/Security/Osäkra_lösenord](https://developer.mozilla.org/sv-se/docs/Web/Security/Osäkra_lösenord) → [/sv-se/docs/Web/Security/Insecure_passwords](https://unslugged.content.dev.mdn.mozit.cloud/sv-se/docs/Web/Security/Insecure_passwords)
