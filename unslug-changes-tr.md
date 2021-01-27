# tr

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 345 documents.
* Moved 134 document.
  * 11 orphaned documents.
  * 10 conflicting documents.
  * 113 renamed documents.

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

* [/tr/docs/Fennec_(Firefox_Mobile)](https://developer.mozilla.org/tr/docs/Fennec_(Firefox_Mobile)) → [/tr/docs/orphaned/Fennec_(Firefox_Mobile)](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/Fennec_(Firefox_Mobile))
* [/tr/docs/MDN/Community](https://developer.mozilla.org/tr/docs/MDN/Community) → [/tr/docs/orphaned/MDN/Community](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/MDN/Community)
* [/tr/docs/MDN/Contribute/Howto/Editor_incelemesi_nasil_yapilir](https://developer.mozilla.org/tr/docs/MDN/Contribute/Howto/Editor_incelemesi_nasil_yapilir) → [/tr/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review)
* [/tr/docs/MDN/Editor/Basics](https://developer.mozilla.org/tr/docs/MDN/Editor/Basics) → [/tr/docs/orphaned/MDN/Editor/Basics](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/MDN/Editor/Basics)
* [/tr/docs/MDN/Editor](https://developer.mozilla.org/tr/docs/MDN/Editor) → [/tr/docs/orphaned/MDN/Editor](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/MDN/Editor)
* [/tr/docs/MDN/Kuma/Server_charts](https://developer.mozilla.org/tr/docs/MDN/Kuma/Server_charts) → [/tr/docs/orphaned/MDN/Kuma/Server_charts](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/MDN/Kuma/Server_charts)
* [/tr/docs/MDN/Tools/Page_watching](https://developer.mozilla.org/tr/docs/MDN/Tools/Page_watching) → [/tr/docs/orphaned/MDN/Tools/Page_watching](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/MDN/Tools/Page_watching)
* [/tr/docs/Mozilla/Eklentiler/WebExtensions/Deneyiminize_web-ext_ile_başlayın](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler/WebExtensions/Deneyiminize_web-ext_ile_başlayın) → [/tr/docs/orphaned/Mozilla/Add-ons/WebExtensions/Getting_started_with_web-ext](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/Mozilla/Add-ons/WebExtensions/Getting_started_with_web-ext)
* [/tr/docs/Tr](https://developer.mozilla.org/tr/docs/Tr) → [/tr/docs/orphaned/Tr](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/Tr)
* [/tr/docs/Web/HTML-Alani](https://developer.mozilla.org/tr/docs/Web/HTML-Alani) → [/tr/docs/orphaned/Web/HTML-Alani](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/Web/HTML-Alani)
* [/tr/docs/Web/JavaScript/Reference/Global_Objects/Array/prototype](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Global_Objects/Array/prototype) → [/tr/docs/orphaned/Web/JavaScript/Reference/Global_Objects/Array/prototype](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/orphaned/Web/JavaScript/Reference/Global_Objects/Array/prototype)

### Conflicting
* [/tr/docs/Web/Guide/CSS/Getting_started/Cascading_and_inheritance](https://developer.mozilla.org/tr/docs/Web/Guide/CSS/Getting_started/Cascading_and_inheritance) → [/tr/docs/conflicting/Learn/CSS/Building_blocks/Cascade_and_inheritance](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Learn/CSS/Building_blocks/Cascade_and_inheritance)
* [/tr/docs/Web/Guide/CSS/Getting_started/css_nedir](https://developer.mozilla.org/tr/docs/Web/Guide/CSS/Getting_started/css_nedir) → [/tr/docs/conflicting/Learn/CSS/First_steps/How_CSS_works](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Learn/CSS/First_steps/How_CSS_works)
* [/tr/docs/Web/Guide/CSS/Getting_started/How_CSS_works](https://developer.mozilla.org/tr/docs/Web/Guide/CSS/Getting_started/How_CSS_works) → [/tr/docs/conflicting/Learn/CSS/First_steps/How_CSS_works_bb137d8ec11d5e9680f32049e9a3cb26](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Learn/CSS/First_steps/How_CSS_works_bb137d8ec11d5e9680f32049e9a3cb26)
* [/tr/docs/Web/Guide/CSS/Getting_started](https://developer.mozilla.org/tr/docs/Web/Guide/CSS/Getting_started) → [/tr/docs/conflicting/Learn/CSS/First_steps](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Learn/CSS/First_steps)
* [/tr/docs/Web/Guide/CSS/Getting_started/Why_use_CSS](https://developer.mozilla.org/tr/docs/Web/Guide/CSS/Getting_started/Why_use_CSS) → [/tr/docs/conflicting/Learn/CSS/First_steps/How_CSS_works_64ba4331a7a5f4319c6e06b06ccdd521](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Learn/CSS/First_steps/How_CSS_works_64ba4331a7a5f4319c6e06b06ccdd521)
* [/tr/docs/Web/JavaScript/Reference/Global_Objects/Boolean/prototype](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Global_Objects/Boolean/prototype) → [/tr/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Boolean](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Boolean)
* [/tr/docs/Web/JavaScript/Reference/Global_Objects/Map/prototype](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Global_Objects/Map/prototype) → [/tr/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Map](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Map)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/Arithmetic_Operators](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/Arithmetic_Operators) → [/tr/docs/conflicting/Web/JavaScript/Reference/Operators](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Web/JavaScript/Reference/Operators)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/Bitwise_Operators](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/Bitwise_Operators) → [/tr/docs/conflicting/Web/JavaScript/Reference/Operators_3b90ea9617c66e4283e266b64ea7ae4a](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Web/JavaScript/Reference/Operators_3b90ea9617c66e4283e266b64ea7ae4a)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/Mantiksal_Operatorler](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/Mantiksal_Operatorler) → [/tr/docs/conflicting/Web/JavaScript/Reference/Operators_603c79383d36dadbe5083df806de5999](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/conflicting/Web/JavaScript/Reference/Operators_603c79383d36dadbe5083df806de5999)

### Renamed
* [/tr/docs/Araclar/Browser_Console](https://developer.mozilla.org/tr/docs/Araclar/Browser_Console) → [/tr/docs/Tools/Browser_Console](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Browser_Console)
* [/tr/docs/Araclar/HataAyıklayıcı](https://developer.mozilla.org/tr/docs/Araclar/HataAyıklayıcı) → [/tr/docs/Tools/Debugger](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Debugger)
* [/tr/docs/Araclar](https://developer.mozilla.org/tr/docs/Araclar) → [/tr/docs/Tools](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools)
* [/tr/docs/Araclar/Page_Inspector](https://developer.mozilla.org/tr/docs/Araclar/Page_Inspector) → [/tr/docs/Tools/Page_Inspector](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Page_Inspector)
* [/tr/docs/Araclar/Performance](https://developer.mozilla.org/tr/docs/Araclar/Performance) → [/tr/docs/Tools/Performance](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Performance)
* [/tr/docs/Araclar/Remote_Debugging](https://developer.mozilla.org/tr/docs/Araclar/Remote_Debugging) → [/tr/docs/Tools/Remote_Debugging](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Remote_Debugging)
* [/tr/docs/Araclar/Web_Konsolu/Bolunmus_Konsol](https://developer.mozilla.org/tr/docs/Araclar/Web_Konsolu/Bolunmus_Konsol) → [/tr/docs/Tools/Web_Console/Split_console](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Web_Console/Split_console)
* [/tr/docs/Araclar/Web_Konsolu](https://developer.mozilla.org/tr/docs/Araclar/Web_Konsolu) → [/tr/docs/Tools/Web_Console](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Web_Console)
* [/tr/docs/Araclar/Web_Konsolu/Komut_Satiri_Tercumani](https://developer.mozilla.org/tr/docs/Araclar/Web_Konsolu/Komut_Satiri_Tercumani) → [/tr/docs/Tools/Web_Console/The_command_line_interpreter](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Web_Console/The_command_line_interpreter)
* [/tr/docs/Araclar/Web_Konsolu/Web_Konsolunu_Acmak](https://developer.mozilla.org/tr/docs/Araclar/Web_Konsolu/Web_Konsolunu_Acmak) → [/tr/docs/Tools/Web_Console/UI_Tour](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Web_Console/UI_Tour)
* [/tr/docs/Araclar/Web_Konsolu/Zengin_Cikti](https://developer.mozilla.org/tr/docs/Araclar/Web_Konsolu/Zengin_Cikti) → [/tr/docs/Tools/Web_Console/Rich_output](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Tools/Web_Console/Rich_output)
* [/tr/docs/Glossary/Nesne](https://developer.mozilla.org/tr/docs/Glossary/Nesne) → [/tr/docs/Glossary/Object](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Glossary/Object)
* [/tr/docs/Glossary/NYP](https://developer.mozilla.org/tr/docs/Glossary/NYP) → [/tr/docs/Glossary/OOP](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Glossary/OOP)
* [/tr/docs/Glossary/Protokol](https://developer.mozilla.org/tr/docs/Glossary/Protokol) → [/tr/docs/Glossary/Protocol](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Glossary/Protocol)
* [/tr/docs/Glossary/Web_Tarayıcısı](https://developer.mozilla.org/tr/docs/Glossary/Web_Tarayıcısı) → [/tr/docs/Glossary/Browser](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Glossary/Browser)
* [/tr/docs/HTML/Element/aside](https://developer.mozilla.org/tr/docs/HTML/Element/aside) → [/tr/docs/Web/HTML/Element/aside](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTML/Element/aside)
* [/tr/docs/HTML/Element/head](https://developer.mozilla.org/tr/docs/HTML/Element/head) → [/tr/docs/Web/HTML/Element/head](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTML/Element/head)
* [/tr/docs/HTML/Element/hgroup](https://developer.mozilla.org/tr/docs/HTML/Element/hgroup) → [/tr/docs/Web/HTML/Element/hgroup](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTML/Element/hgroup)
* [/tr/docs/HTML/Element](https://developer.mozilla.org/tr/docs/HTML/Element) → [/tr/docs/Web/HTML/Element](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTML/Element)
* [/tr/docs/HTML/Element/li](https://developer.mozilla.org/tr/docs/HTML/Element/li) → [/tr/docs/Web/HTML/Element/li](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTML/Element/li)
* [/tr/docs/HTML/Element/link](https://developer.mozilla.org/tr/docs/HTML/Element/link) → [/tr/docs/Web/HTML/Element/link](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTML/Element/link)
* [/tr/docs/Learn/Common_questions/Tarayıcı_geliştirici_araçları_araçları_nelerdir](https://developer.mozilla.org/tr/docs/Learn/Common_questions/Tarayıcı_geliştirici_araçları_araçları_nelerdir) → [/tr/docs/Learn/Common_questions/What_are_browser_developer_tools](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Common_questions/What_are_browser_developer_tools)
* [/tr/docs/MDN_onunda](https://developer.mozilla.org/tr/docs/MDN_onunda) → [/tr/docs/MDN/At_ten](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/MDN/At_ten)
* [/tr/docs/MDN/Contribute/Howto/Sayfalar_nasil_olusturulur_duzenlenir](https://developer.mozilla.org/tr/docs/MDN/Contribute/Howto/Sayfalar_nasil_olusturulur_duzenlenir) → [/tr/docs/MDN/Contribute/Howto/Create_and_edit_pages](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/MDN/Contribute/Howto/Create_and_edit_pages)
* [/tr/docs/MDN/Hakkinda](https://developer.mozilla.org/tr/docs/MDN/Hakkinda) → [/tr/docs/MDN/About](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/MDN/About)
* [/tr/docs/MDN/Kuma](https://developer.mozilla.org/tr/docs/MDN/Kuma) → [/tr/docs/MDN/Yari](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/MDN/Yari)
* [/tr/docs/MDN/Kuma/Troubleshooting_KumaScript_errors](https://developer.mozilla.org/tr/docs/MDN/Kuma/Troubleshooting_KumaScript_errors) → [/tr/docs/MDN/Tools/KumaScript/Troubleshooting](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/MDN/Tools/KumaScript/Troubleshooting)
* [/tr/docs/Mozilla/Developer_guide/Kaynak_Kod](https://developer.mozilla.org/tr/docs/Mozilla/Developer_guide/Kaynak_Kod) → [/tr/docs/Mozilla/Developer_guide/Source_Code](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Developer_guide/Source_Code)
* [/tr/docs/Mozilla/Eklentiler](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler) → [/tr/docs/Mozilla/Add-ons](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Add-ons)
* [/tr/docs/Mozilla/Eklentiler/WebExtensions/Eklenti_nedir](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler/WebExtensions/Eklenti_nedir) → [/tr/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions)
* [/tr/docs/Mozilla/Eklentiler/WebExtensions/Extending_the_developer_tools](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler/WebExtensions/Extending_the_developer_tools) → [/tr/docs/Mozilla/Add-ons/WebExtensions/Extending_the_developer_tools](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Add-ons/WebExtensions/Extending_the_developer_tools)
* [/tr/docs/Mozilla/Eklentiler/WebExtensions/İlk_Eklentin](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler/WebExtensions/İlk_Eklentin) → [/tr/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
* [/tr/docs/Mozilla/Eklentiler/WebExtensions](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler/WebExtensions) → [/tr/docs/Mozilla/Add-ons/WebExtensions](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Add-ons/WebExtensions)
* [/tr/docs/Mozilla/Eklentiler/WebExtensions/user_interface](https://developer.mozilla.org/tr/docs/Mozilla/Eklentiler/WebExtensions/user_interface) → [/tr/docs/Mozilla/Add-ons/WebExtensions/user_interface](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Mozilla/Add-ons/WebExtensions/user_interface)
* [/tr/docs/Öğren/CSS/CSS_layout](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_layout) → [/tr/docs/Learn/CSS/CSS_layout](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/CSS_layout)
* [/tr/docs/Öğren/CSS/CSS_layout/Introduction](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_layout/Introduction) → [/tr/docs/Learn/CSS/CSS_layout/Introduction](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/CSS_layout/Introduction)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Backgrounds_and_borders](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Backgrounds_and_borders) → [/tr/docs/Learn/CSS/Building_blocks/Backgrounds_and_borders](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Backgrounds_and_borders)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Cascade_and_inheritance](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Cascade_and_inheritance) → [/tr/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Debugging_CSS](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Debugging_CSS) → [/tr/docs/Learn/CSS/Building_blocks/Debugging_CSS](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Debugging_CSS)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Handling_different_text_directions](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Handling_different_text_directions) → [/tr/docs/Learn/CSS/Building_blocks/Handling_different_text_directions](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Handling_different_text_directions)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Images_media_form_elements](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Images_media_form_elements) → [/tr/docs/Learn/CSS/Building_blocks/Images_media_form_elements](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Images_media_form_elements)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari) → [/tr/docs/Learn/CSS/Building_blocks](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Organizing](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Organizing) → [/tr/docs/Learn/CSS/Building_blocks/Organizing](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Organizing)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Overflow_Tasks](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Overflow_Tasks) → [/tr/docs/Learn/CSS/Building_blocks/Overflow_Tasks](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Overflow_Tasks)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Overflowing_content](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Overflowing_content) → [/tr/docs/Learn/CSS/Building_blocks/Overflowing_content](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Overflowing_content)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Selectors](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Selectors) → [/tr/docs/Web/CSS/CSS_Selectors](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/CSS/CSS_Selectors)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Sizing_items_in_CSS](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Sizing_items_in_CSS) → [/tr/docs/Learn/CSS/Building_blocks/Sizing_items_in_CSS](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Sizing_items_in_CSS)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Sizing_tasks](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Sizing_tasks) → [/tr/docs/Learn/CSS/Building_blocks/Sizing_tasks](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Sizing_tasks)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Styling_tables](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Styling_tables) → [/tr/docs/Learn/CSS/Building_blocks/Styling_tables](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Styling_tables)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Test_your_skills_backgrounds_and_borders](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Test_your_skills_backgrounds_and_borders) → [/tr/docs/Learn/CSS/Building_blocks/Test_your_skills_backgrounds_and_borders](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Test_your_skills_backgrounds_and_borders)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/The_box_model](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/The_box_model) → [/tr/docs/Learn/CSS/Building_blocks/The_box_model](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/The_box_model)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Values_and_units](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Values_and_units) → [/tr/docs/Learn/CSS/Building_blocks/Values_and_units](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Values_and_units)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Values_tasks](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Values_tasks) → [/tr/docs/Learn/CSS/Building_blocks/Values_tasks](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Values_tasks)
* [/tr/docs/Öğren/CSS/CSS_yapi_taslari/Writing_Modes_Tasks](https://developer.mozilla.org/tr/docs/Öğren/CSS/CSS_yapi_taslari/Writing_Modes_Tasks) → [/tr/docs/Learn/CSS/Building_blocks/Writing_Modes_Tasks](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Building_blocks/Writing_Modes_Tasks)
* [/tr/docs/Öğren/CSS/Ilk_adimlar/CSS_nasil_calisir](https://developer.mozilla.org/tr/docs/Öğren/CSS/Ilk_adimlar/CSS_nasil_calisir) → [/tr/docs/Learn/CSS/First_steps/How_CSS_works](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/First_steps/How_CSS_works)
* [/tr/docs/Öğren/CSS/Ilk_adimlar/CSS_Nedir](https://developer.mozilla.org/tr/docs/Öğren/CSS/Ilk_adimlar/CSS_Nedir) → [/tr/docs/Learn/CSS/First_steps/What_is_CSS](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/First_steps/What_is_CSS)
* [/tr/docs/Öğren/CSS/Ilk_adimlar/Getting_started](https://developer.mozilla.org/tr/docs/Öğren/CSS/Ilk_adimlar/Getting_started) → [/tr/docs/Learn/CSS/First_steps/Getting_started](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/First_steps/Getting_started)
* [/tr/docs/Öğren/CSS/Ilk_adimlar/How_CSS_is_structured](https://developer.mozilla.org/tr/docs/Öğren/CSS/Ilk_adimlar/How_CSS_is_structured) → [/tr/docs/Learn/CSS/First_steps/How_CSS_is_structured](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/First_steps/How_CSS_is_structured)
* [/tr/docs/Öğren/CSS/Ilk_adimlar](https://developer.mozilla.org/tr/docs/Öğren/CSS/Ilk_adimlar) → [/tr/docs/Learn/CSS/First_steps](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/First_steps)
* [/tr/docs/Öğren/CSS/Ilk_adimlar/Ogrendiklerinizi_Uygulayın](https://developer.mozilla.org/tr/docs/Öğren/CSS/Ilk_adimlar/Ogrendiklerinizi_Uygulayın) → [/tr/docs/Learn/CSS/First_steps/Using_your_new_knowledge](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/First_steps/Using_your_new_knowledge)
* [/tr/docs/Öğren/CSS](https://developer.mozilla.org/tr/docs/Öğren/CSS) → [/tr/docs/Learn/CSS](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS)
* [/tr/docs/Öğren/CSS/Styling_text/Fundamentals](https://developer.mozilla.org/tr/docs/Öğren/CSS/Styling_text/Fundamentals) → [/tr/docs/Learn/CSS/Styling_text/Fundamentals](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Styling_text/Fundamentals)
* [/tr/docs/Öğren/CSS/Styling_text](https://developer.mozilla.org/tr/docs/Öğren/CSS/Styling_text) → [/tr/docs/Learn/CSS/Styling_text](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Styling_text)
* [/tr/docs/Öğren/CSS/Styling_text/Styling_links](https://developer.mozilla.org/tr/docs/Öğren/CSS/Styling_text/Styling_links) → [/tr/docs/Learn/CSS/Styling_text/Styling_links](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Styling_text/Styling_links)
* [/tr/docs/Öğren/CSS/Styling_text/Styling_lists](https://developer.mozilla.org/tr/docs/Öğren/CSS/Styling_text/Styling_lists) → [/tr/docs/Learn/CSS/Styling_text/Styling_lists](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Styling_text/Styling_lists)
* [/tr/docs/Öğren/CSS/Styling_text/Typesetting_a_homepage](https://developer.mozilla.org/tr/docs/Öğren/CSS/Styling_text/Typesetting_a_homepage) → [/tr/docs/Learn/CSS/Styling_text/Typesetting_a_homepage](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Styling_text/Typesetting_a_homepage)
* [/tr/docs/Öğren/CSS/Styling_text/Web_fonts](https://developer.mozilla.org/tr/docs/Öğren/CSS/Styling_text/Web_fonts) → [/tr/docs/Learn/CSS/Styling_text/Web_fonts](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/CSS/Styling_text/Web_fonts)
* [/tr/docs/Öğren/Front-end_web_developer](https://developer.mozilla.org/tr/docs/Öğren/Front-end_web_developer) → [/tr/docs/Learn/Front-end_web_developer](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Front-end_web_developer)
* [/tr/docs/Öğren/Getting_started_with_the_web/How_the_Web_works](https://developer.mozilla.org/tr/docs/Öğren/Getting_started_with_the_web/How_the_Web_works) → [/tr/docs/Learn/Getting_started_with_the_web/How_the_Web_works](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
* [/tr/docs/Öğren/Getting_started_with_the_web](https://developer.mozilla.org/tr/docs/Öğren/Getting_started_with_the_web) → [/tr/docs/Learn/Getting_started_with_the_web](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Getting_started_with_the_web)
* [/tr/docs/Öğren/Getting_started_with_the_web/Installing_basic_software](https://developer.mozilla.org/tr/docs/Öğren/Getting_started_with_the_web/Installing_basic_software) → [/tr/docs/Learn/Getting_started_with_the_web/Installing_basic_software](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/tr/docs/Öğren/Getting_started_with_the_web/JavaScript_basics](https://developer.mozilla.org/tr/docs/Öğren/Getting_started_with_the_web/JavaScript_basics) → [/tr/docs/Learn/Getting_started_with_the_web/JavaScript_basics](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
* [/tr/docs/Öğren/Getting_started_with_the_web/Web_siteniz_nasil_gorunecek](https://developer.mozilla.org/tr/docs/Öğren/Getting_started_with_the_web/Web_siteniz_nasil_gorunecek) → [/tr/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
* [/tr/docs/Öğren/HTML](https://developer.mozilla.org/tr/docs/Öğren/HTML) → [/tr/docs/Learn/HTML](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/HTML)
* [/tr/docs/Öğren/HTML/Introduction_to_HTML/Başlangıç](https://developer.mozilla.org/tr/docs/Öğren/HTML/Introduction_to_HTML/Başlangıç) → [/tr/docs/Learn/HTML/Introduction_to_HTML/Getting_started](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
* [/tr/docs/Öğren/HTML/Introduction_to_HTML](https://developer.mozilla.org/tr/docs/Öğren/HTML/Introduction_to_HTML) → [/tr/docs/Learn/HTML/Introduction_to_HTML](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/HTML/Introduction_to_HTML)
* [/tr/docs/Öğren](https://developer.mozilla.org/tr/docs/Öğren) → [/tr/docs/Learn](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn)
* [/tr/docs/Öğren/JavaScript/First_steps](https://developer.mozilla.org/tr/docs/Öğren/JavaScript/First_steps) → [/tr/docs/Learn/JavaScript/First_steps](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/JavaScript/First_steps)
* [/tr/docs/Öğren/JavaScript/First_steps/Javascripte_giris](https://developer.mozilla.org/tr/docs/Öğren/JavaScript/First_steps/Javascripte_giris) → [/tr/docs/Learn/JavaScript/First_steps/A_first_splash](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/JavaScript/First_steps/A_first_splash)
* [/tr/docs/Öğren/JavaScript](https://developer.mozilla.org/tr/docs/Öğren/JavaScript) → [/tr/docs/Learn/JavaScript](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/JavaScript)
* [/tr/docs/Öğren/JavaScript/Objeler/Basics](https://developer.mozilla.org/tr/docs/Öğren/JavaScript/Objeler/Basics) → [/tr/docs/Learn/JavaScript/Objects/Basics](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/JavaScript/Objects/Basics)
* [/tr/docs/Öğren/JavaScript/Objeler](https://developer.mozilla.org/tr/docs/Öğren/JavaScript/Objeler) → [/tr/docs/Learn/JavaScript/Objects](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/JavaScript/Objects)
* [/tr/docs/Öğren/Server-side/Django/Authentication](https://developer.mozilla.org/tr/docs/Öğren/Server-side/Django/Authentication) → [/tr/docs/Learn/Server-side/Django/Authentication](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Server-side/Django/Authentication)
* [/tr/docs/Öğren/Server-side/Django](https://developer.mozilla.org/tr/docs/Öğren/Server-side/Django) → [/tr/docs/Learn/Server-side/Django](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Server-side/Django)
* [/tr/docs/Öğren/Server-side/Django/Sessions](https://developer.mozilla.org/tr/docs/Öğren/Server-side/Django/Sessions) → [/tr/docs/Learn/Server-side/Django/Sessions](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Server-side/Django/Sessions)
* [/tr/docs/Öğren/Server-side/Django/website_iskeleti](https://developer.mozilla.org/tr/docs/Öğren/Server-side/Django/website_iskeleti) → [/tr/docs/Learn/Server-side/Django/skeleton_website](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Server-side/Django/skeleton_website)
* [/tr/docs/Öğren/Server-side](https://developer.mozilla.org/tr/docs/Öğren/Server-side) → [/tr/docs/Learn/Server-side](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Learn/Server-side)
* [/tr/docs/Oyunlar](https://developer.mozilla.org/tr/docs/Oyunlar) → [/tr/docs/Games](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Games)
* [/tr/docs/Security/MixedContent](https://developer.mozilla.org/tr/docs/Security/MixedContent) → [/tr/docs/Web/Security/Mixed_content](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Security/Mixed_content)
* [/tr/docs/Security/Zatıf_İmza_Algoritması](https://developer.mozilla.org/tr/docs/Security/Zatıf_İmza_Algoritması) → [/tr/docs/Web/Security/Weak_Signature_Algorithm](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Security/Weak_Signature_Algorithm)
* [/tr/docs/Web/API/Tuval_Arabirimi](https://developer.mozilla.org/tr/docs/Web/API/Tuval_Arabirimi) → [/tr/docs/Web/API/Canvas_API](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/API/Canvas_API)
* [/tr/docs/Web/Bildiri](https://developer.mozilla.org/tr/docs/Web/Bildiri) → [/tr/docs/Web/Manifest](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Manifest)
* [/tr/docs/Web/CSS/box_model](https://developer.mozilla.org/tr/docs/Web/CSS/box_model) → [/tr/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
* [/tr/docs/Web/CSS/Sınıf_seçicileri](https://developer.mozilla.org/tr/docs/Web/CSS/Sınıf_seçicileri) → [/tr/docs/Web/CSS/Class_selectors](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/CSS/Class_selectors)
* [/tr/docs/Web/CSS/Tip_secicileri](https://developer.mozilla.org/tr/docs/Web/CSS/Tip_secicileri) → [/tr/docs/Web/CSS/Type_selectors](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/CSS/Type_selectors)
* [/tr/docs/Web/Guide/Çizgeler](https://developer.mozilla.org/tr/docs/Web/Guide/Çizgeler) → [/tr/docs/Web/Guide/Graphics](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Guide/Graphics)
* [/tr/docs/Web/Guide/CSS/Sayaçlar](https://developer.mozilla.org/tr/docs/Web/Guide/CSS/Sayaçlar) → [/tr/docs/Web/CSS/CSS_Lists_and_Counters/Using_CSS_counters](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/CSS/CSS_Lists_and_Counters/Using_CSS_counters)
* [/tr/docs/Web/Güvenlik](https://developer.mozilla.org/tr/docs/Web/Güvenlik) → [/tr/docs/Web/Security](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Security)
* [/tr/docs/Web/Güvenlik/Transport_Layer_Security](https://developer.mozilla.org/tr/docs/Web/Güvenlik/Transport_Layer_Security) → [/tr/docs/Web/Security/Transport_Layer_Security](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Security/Transport_Layer_Security)
* [/tr/docs/Web/HTML/HTML5](https://developer.mozilla.org/tr/docs/Web/HTML/HTML5) → [/tr/docs/Web/Guide/HTML/HTML5](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/Guide/HTML/HTML5)
* [/tr/docs/Web/HTTP/metotlar](https://developer.mozilla.org/tr/docs/Web/HTTP/metotlar) → [/tr/docs/Web/HTTP/Methods](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTTP/Methods)
* [/tr/docs/Web/HTTP/Oturum](https://developer.mozilla.org/tr/docs/Web/HTTP/Oturum) → [/tr/docs/Web/HTTP/Session](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/HTTP/Session)
* [/tr/docs/Web/JavaScript/Guide/Fonksiyonlar](https://developer.mozilla.org/tr/docs/Web/JavaScript/Guide/Fonksiyonlar) → [/tr/docs/Web/JavaScript/Guide/Functions](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Guide/Functions)
* [/tr/docs/Web/JavaScript/Guide/Ifadeler](https://developer.mozilla.org/tr/docs/Web/JavaScript/Guide/Ifadeler) → [/tr/docs/Web/JavaScript/Guide/Control_flow_and_error_handling](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
* [/tr/docs/Web/JavaScript/Guide/Nesneler_ile_çalışmak](https://developer.mozilla.org/tr/docs/Web/JavaScript/Guide/Nesneler_ile_çalışmak) → [/tr/docs/Web/JavaScript/Guide/Working_with_Objects](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Guide/Working_with_Objects)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/function*](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/function*) → [/tr/docs/Web/JavaScript/Reference/Operators/function*](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Reference/Operators/function*)
* [/tr/docs/Web/JavaScript/Reference/Operatörler](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler) → [/tr/docs/Web/JavaScript/Reference/Operators](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Reference/Operators)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/instanceof](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/instanceof) → [/tr/docs/Web/JavaScript/Reference/Operators/instanceof](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Reference/Operators/instanceof)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/super](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/super) → [/tr/docs/Web/JavaScript/Reference/Operators/super](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Reference/Operators/super)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/this](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/this) → [/tr/docs/Web/JavaScript/Reference/Operators/this](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Reference/Operators/this)
* [/tr/docs/Web/JavaScript/Reference/Operatörler/typeof](https://developer.mozilla.org/tr/docs/Web/JavaScript/Reference/Operatörler/typeof) → [/tr/docs/Web/JavaScript/Reference/Operators/typeof](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Reference/Operators/typeof)
* [/tr/docs/Web/JavaScript/Veri_Yapısı](https://developer.mozilla.org/tr/docs/Web/JavaScript/Veri_Yapısı) → [/tr/docs/Web/JavaScript/Data_structures](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/JavaScript/Data_structures)
* [/tr/docs/Web/CSS/marjin](https://developer.mozilla.org/tr/docs/Web/CSS/marjin) → [/tr/docs/Web/CSS/margin](https://unslugged.content.dev.mdn.mozit.cloud/tr/docs/Web/CSS/margin)
