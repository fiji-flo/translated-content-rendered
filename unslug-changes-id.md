# id

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 304 documents.
* Moved 54 document.
  * 8 orphaned documents.
  * 7 conflicting documents.
  * 39 renamed documents.

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

* [/id/docs/Learn/How_to_contribute](https://developer.mozilla.org/id/docs/Learn/How_to_contribute) → [/id/docs/orphaned/Learn/How_to_contribute](/id/docs/orphaned/Learn/How_to_contribute)
* [/id/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/id/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/id/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/id/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/id/docs/MDN/Contribute/Howto/Do_a_technical_review](https://developer.mozilla.org/id/docs/MDN/Contribute/Howto/Do_a_technical_review) → [/id/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review](/id/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review)
* [/id/docs/MDN/Contribute/Howto/Do_an_editorial_review](https://developer.mozilla.org/id/docs/MDN/Contribute/Howto/Do_an_editorial_review) → [/id/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review](/id/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review)
* [/id/docs/MDN/Contribute/Howto/Set_the_summary_for_a_page](https://developer.mozilla.org/id/docs/MDN/Contribute/Howto/Set_the_summary_for_a_page) → [/id/docs/orphaned/MDN/Contribute/Howto/Set_the_summary_for_a_page](/id/docs/orphaned/MDN/Contribute/Howto/Set_the_summary_for_a_page)
* [/id/docs/MDN/Komunitas/Conversations](https://developer.mozilla.org/id/docs/MDN/Komunitas/Conversations) → [/id/docs/orphaned/MDN/Community/Conversations](/id/docs/orphaned/MDN/Community/Conversations)
* [/id/docs/MDN/Komunitas](https://developer.mozilla.org/id/docs/MDN/Komunitas) → [/id/docs/orphaned/MDN/Community](/id/docs/orphaned/MDN/Community)
* [/id/docs/MDN/User_guide/Menghapus_halaman](https://developer.mozilla.org/id/docs/MDN/User_guide/Menghapus_halaman) → [/id/docs/orphaned/MDN/Tools/Page_deletion](/id/docs/orphaned/MDN/Tools/Page_deletion)

### Conflicting
* [/id/docs/Learn/Web_Mechanics](https://developer.mozilla.org/id/docs/Learn/Web_Mechanics) → [/id/docs/conflicting/Learn/Common_questions](/id/docs/conflicting/Learn/Common_questions)
* [/id/docs/MDN/Contribute/Tugas](https://developer.mozilla.org/id/docs/MDN/Contribute/Tugas) → [/id/docs/conflicting/MDN/Contribute/Getting_started](/id/docs/conflicting/MDN/Contribute/Getting_started)
* [/id/docs/Pengembangan_Web](https://developer.mozilla.org/id/docs/Pengembangan_Web) → [/id/docs/conflicting/Web/Guide](/id/docs/conflicting/Web/Guide)
* [/id/docs/Web/Guide/API/WebRTC](https://developer.mozilla.org/id/docs/Web/Guide/API/WebRTC) → [/id/docs/conflicting/Web/API/WebRTC_API](/id/docs/conflicting/Web/API/WebRTC_API)
* [/id/docs/Web/JavaScript/Panduan/Tentang](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/Tentang) → [/id/docs/conflicting/Web/JavaScript/Guide/Introduction](/id/docs/conflicting/Web/JavaScript/Guide/Introduction)
* [/id/docs/Web/JavaScript/Reference/Global_Objects/Function/prototype](https://developer.mozilla.org/id/docs/Web/JavaScript/Reference/Global_Objects/Function/prototype) → [/id/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Function](/id/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Function)
* [/id/docs/Web/JavaScript/Reference/Global_Objects/String/purwarupa](https://developer.mozilla.org/id/docs/Web/JavaScript/Reference/Global_Objects/String/purwarupa) → [/id/docs/conflicting/Web/JavaScript/Reference/Global_Objects/String](/id/docs/conflicting/Web/JavaScript/Reference/Global_Objects/String)

### Renamed
* [/id/docs/Developer_Guide](https://developer.mozilla.org/id/docs/Developer_Guide) → [/id/docs/Mozilla/Developer_guide](/id/docs/Mozilla/Developer_guide)
* [/id/docs/Developer_Guide/Virtual_ARM_di_Lingkungan_Linux](https://developer.mozilla.org/id/docs/Developer_Guide/Virtual_ARM_di_Lingkungan_Linux) → [/id/docs/Mozilla/Developer_guide/Virtual_ARM_Linux_environment](/id/docs/Mozilla/Developer_guide/Virtual_ARM_Linux_environment)
* [/id/docs/Glossary/Algoritma](https://developer.mozilla.org/id/docs/Glossary/Algoritma) → [/id/docs/Glossary/Algorithm](/id/docs/Glossary/Algorithm)
* [/id/docs/Learn/Common_questions/Bagaimana_cara_kerja_Internet](https://developer.mozilla.org/id/docs/Learn/Common_questions/Bagaimana_cara_kerja_Internet) → [/id/docs/Learn/Common_questions/How_does_the_Internet_work](/id/docs/Learn/Common_questions/How_does_the_Internet_work)
* [/id/docs/Learn/Common_questions/Berfikir_sebelum_membuat_kode](https://developer.mozilla.org/id/docs/Learn/Common_questions/Berfikir_sebelum_membuat_kode) → [/id/docs/Learn/Common_questions/Thinking_before_coding](/id/docs/Learn/Common_questions/Thinking_before_coding)
* [/id/docs/Learn/Getting_started_with_the_web/Akan_terlihat_seperti_apa_website_anda](https://developer.mozilla.org/id/docs/Learn/Getting_started_with_the_web/Akan_terlihat_seperti_apa_website_anda) → [/id/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like](/id/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
* [/id/docs/Learn/Getting_started_with_the_web/Mengelola_file](https://developer.mozilla.org/id/docs/Learn/Getting_started_with_the_web/Mengelola_file) → [/id/docs/Learn/Getting_started_with_the_web/Dealing_with_files](/id/docs/Learn/Getting_started_with_the_web/Dealing_with_files)
* [/id/docs/Learn/HTML/Multimedia_dan_embedding/Adding_vector_graphics_to_the_Web](https://developer.mozilla.org/id/docs/Learn/HTML/Multimedia_dan_embedding/Adding_vector_graphics_to_the_Web) → [/id/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web](/id/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web)
* [/id/docs/Learn/HTML/Multimedia_dan_embedding](https://developer.mozilla.org/id/docs/Learn/HTML/Multimedia_dan_embedding) → [/id/docs/Learn/HTML/Multimedia_and_embedding](/id/docs/Learn/HTML/Multimedia_and_embedding)
* [/id/docs/Learn/HTML/Multimedia_dan_embedding/Responsive_images](https://developer.mozilla.org/id/docs/Learn/HTML/Multimedia_dan_embedding/Responsive_images) → [/id/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images](/id/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
* [/id/docs/Learn/HTML/Pengenalan_HTML/Document_and_website_structure](https://developer.mozilla.org/id/docs/Learn/HTML/Pengenalan_HTML/Document_and_website_structure) → [/id/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure](/id/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
* [/id/docs/Learn/HTML/Pengenalan_HTML/HTML_text_fundamentals](https://developer.mozilla.org/id/docs/Learn/HTML/Pengenalan_HTML/HTML_text_fundamentals) → [/id/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals](/id/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
* [/id/docs/Learn/HTML/Pengenalan_HTML](https://developer.mozilla.org/id/docs/Learn/HTML/Pengenalan_HTML) → [/id/docs/Learn/HTML/Introduction_to_HTML](/id/docs/Learn/HTML/Introduction_to_HTML)
* [/id/docs/Learn/HTML/Pengenalan_HTML/Structuring_a_page_of_content](https://developer.mozilla.org/id/docs/Learn/HTML/Pengenalan_HTML/Structuring_a_page_of_content) → [/id/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content](/id/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content)
* [/id/docs/Learn/HTML/Tabel](https://developer.mozilla.org/id/docs/Learn/HTML/Tabel) → [/id/docs/Learn/HTML/Tables](/id/docs/Learn/HTML/Tables)
* [/id/docs/Learn/JavaScript/Objects/Dasar-dasar](https://developer.mozilla.org/id/docs/Learn/JavaScript/Objects/Dasar-dasar) → [/id/docs/Learn/JavaScript/Objects/Basics](/id/docs/Learn/JavaScript/Objects/Basics)
* [/id/docs/Mozilla/Add-ons/WebExtensions/Apa_Itu_WebExtensions](https://developer.mozilla.org/id/docs/Mozilla/Add-ons/WebExtensions/Apa_Itu_WebExtensions) → [/id/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions](/id/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions)
* [/id/docs/Mozilla/Add-ons/WebExtensions/API/notifikasi](https://developer.mozilla.org/id/docs/Mozilla/Add-ons/WebExtensions/API/notifikasi) → [/id/docs/Mozilla/Add-ons/WebExtensions/API/notifications](/id/docs/Mozilla/Add-ons/WebExtensions/API/notifications)
* [/id/docs/Web/API/API_Push](https://developer.mozilla.org/id/docs/Web/API/API_Push) → [/id/docs/Web/API/Push_API](/id/docs/Web/API/Push_API)
* [/id/docs/Web/CSS/referensi](https://developer.mozilla.org/id/docs/Web/CSS/referensi) → [/id/docs/Web/CSS/Reference](/id/docs/Web/CSS/Reference)
* [/id/docs/Web/Events/error](https://developer.mozilla.org/id/docs/Web/Events/error) → [/id/docs/Web/API/Element/error_event](/id/docs/Web/API/Element/error_event)
* [/id/docs/Web/Guide/CSS/Media_queries](https://developer.mozilla.org/id/docs/Web/Guide/CSS/Media_queries) → [/id/docs/Web/CSS/Media_Queries/Using_media_queries](/id/docs/Web/CSS/Media_Queries/Using_media_queries)
* [/id/docs/Web/Guide/Grafis](https://developer.mozilla.org/id/docs/Web/Guide/Grafis) → [/id/docs/Web/Guide/Graphics](/id/docs/Web/Guide/Graphics)
* [/id/docs/Web/Guide/HTML/Forms](https://developer.mozilla.org/id/docs/Web/Guide/HTML/Forms) → [/id/docs/Learn/Forms](/id/docs/Learn/Forms)
* [/id/docs/Web/HTTP/Gambaran](https://developer.mozilla.org/id/docs/Web/HTTP/Gambaran) → [/id/docs/Web/HTTP/Overview](/id/docs/Web/HTTP/Overview)
* [/id/docs/Web/HTTP/Proxy_servers_and_tunneling/Proxy_Auto-Configuration_(PAC)_file](https://developer.mozilla.org/id/docs/Web/HTTP/Proxy_servers_and_tunneling/Proxy_Auto-Configuration_(PAC)_file) → [/id/docs/Web/HTTP/Proxy_servers_and_tunneling/Proxy_Auto-Configuration_PAC_file](/id/docs/Web/HTTP/Proxy_servers_and_tunneling/Proxy_Auto-Configuration_PAC_file)
* [/id/docs/Web/JavaScript/Inheritance_dan_prototype_chain](https://developer.mozilla.org/id/docs/Web/JavaScript/Inheritance_dan_prototype_chain) → [/id/docs/Web/JavaScript/Inheritance_and_the_prototype_chain](/id/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
* [/id/docs/Web/JavaScript/Panduan/Closures](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/Closures) → [/id/docs/Web/JavaScript/Closures](/id/docs/Web/JavaScript/Closures)
* [/id/docs/Web/JavaScript/Panduan](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan) → [/id/docs/Web/JavaScript/Guide](/id/docs/Web/JavaScript/Guide)
* [/id/docs/Web/JavaScript/Panduan/Loops_and_iteration](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/Loops_and_iteration) → [/id/docs/Web/JavaScript/Guide/Loops_and_iteration](/id/docs/Web/JavaScript/Guide/Loops_and_iteration)
* [/id/docs/Web/JavaScript/Panduan/Numbers_and_dates](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/Numbers_and_dates) → [/id/docs/Web/JavaScript/Guide/Numbers_and_dates](/id/docs/Web/JavaScript/Guide/Numbers_and_dates)
* [/id/docs/Web/JavaScript/Panduan/pengenalan](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/pengenalan) → [/id/docs/Web/JavaScript/Guide/Introduction](/id/docs/Web/JavaScript/Guide/Introduction)
* [/id/docs/Web/JavaScript/Panduan/Values,_variables,_and_literals](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/Values,_variables,_and_literals) → [/id/docs/Web/JavaScript/Guide/Grammar_and_types](/id/docs/Web/JavaScript/Guide/Grammar_and_types)
* [/id/docs/Web/JavaScript/Panduan/Working_with_Objects](https://developer.mozilla.org/id/docs/Web/JavaScript/Panduan/Working_with_Objects) → [/id/docs/Web/JavaScript/Guide/Working_with_Objects](/id/docs/Web/JavaScript/Guide/Working_with_Objects)
* [/id/docs/Web/JavaScript/Reference/Operators/fungsi](https://developer.mozilla.org/id/docs/Web/JavaScript/Reference/Operators/fungsi) → [/id/docs/Web/JavaScript/Reference/Operators/function](/id/docs/Web/JavaScript/Reference/Operators/function)
* [/id/docs/Web/JavaScript/Reference/Statements/fungsi](https://developer.mozilla.org/id/docs/Web/JavaScript/Reference/Statements/fungsi) → [/id/docs/Web/JavaScript/Reference/Statements/function](/id/docs/Web/JavaScript/Reference/Statements/function)
* [/id/docs/Web/JavaScript/sekilas_teknologi_JavaScript](https://developer.mozilla.org/id/docs/Web/JavaScript/sekilas_teknologi_JavaScript) → [/id/docs/Web/JavaScript/JavaScript_technologies_overview](/id/docs/Web/JavaScript/JavaScript_technologies_overview)
* [/id/docs/MDN/User_guide](https://developer.mozilla.org/id/docs/MDN/User_guide) → [/id/docs/MDN/Tools](/id/docs/MDN/Tools)
* [/id/docs/Web/Guide/CSS/Getting_started](https://developer.mozilla.org/id/docs/Web/Guide/CSS/Getting_started) → [/id/docs/Learn/CSS/First_steps](/id/docs/Learn/CSS/First_steps)
