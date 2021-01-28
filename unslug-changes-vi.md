# vi

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 342 documents.
* Moved 62 document.
  * 8 orphaned documents.
  * 5 conflicting documents.
  * 49 renamed documents.

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

* [/vi/docs/Bản_Kê_Khai_Cài_Đặt](https://developer.mozilla.org/vi/docs/Bản_Kê_Khai_Cài_Đặt) → [/vi/docs/orphaned/Bản_Kê_Khai_Cài_Đặt](/vi/docs/orphaned/Bản_Kê_Khai_Cài_Đặt)
* [/vi/docs/DOM_Inspector](https://developer.mozilla.org/vi/docs/DOM_Inspector) → [/vi/docs/orphaned/DOM_Inspector](/vi/docs/orphaned/DOM_Inspector)
* [/vi/docs/Labs-tab](https://developer.mozilla.org/vi/docs/Labs-tab) → [/vi/docs/orphaned/Labs-tab](/vi/docs/orphaned/Labs-tab)
* [/vi/docs/Learn/Dong_gop_cho_khu_vuc_hoc_tap_tren_MDN](https://developer.mozilla.org/vi/docs/Learn/Dong_gop_cho_khu_vuc_hoc_tap_tren_MDN) → [/vi/docs/orphaned/Learn/How_to_contribute](/vi/docs/orphaned/Learn/How_to_contribute)
* [/vi/docs/MDN/Community](https://developer.mozilla.org/vi/docs/MDN/Community) → [/vi/docs/orphaned/MDN/Community](/vi/docs/orphaned/MDN/Community)
* [/vi/docs/MDN/Contribute/Howto/Create_an_MDN_account](https://developer.mozilla.org/vi/docs/MDN/Contribute/Howto/Create_an_MDN_account) → [/vi/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/vi/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/vi/docs/MDN/Contribute/Howto/Do_a_technical_review](https://developer.mozilla.org/vi/docs/MDN/Contribute/Howto/Do_a_technical_review) → [/vi/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review](/vi/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review)
* [/vi/docs/MDN/Contribute/Howto/Do_an_editorial_review](https://developer.mozilla.org/vi/docs/MDN/Contribute/Howto/Do_an_editorial_review) → [/vi/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review](/vi/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review)

### Conflicting
* [/vi/docs/Web/HTML_vi](https://developer.mozilla.org/vi/docs/Web/HTML_vi) → [/vi/docs/conflicting/Web/HTML](/vi/docs/conflicting/Web/HTML)
* [/vi/docs/Web/JavaScript/Reference/Global_Objects/Array/length](https://developer.mozilla.org/vi/docs/Web/JavaScript/Reference/Global_Objects/Array/length) → [/vi/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Array/length](/vi/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Array/length)
* [/vi/docs/Web/Guide/CSS/Getting_started](https://developer.mozilla.org/vi/docs/Web/Guide/CSS/Getting_started) → [/vi/docs/conflicting/Learn/CSS/First_steps](/vi/docs/conflicting/Learn/CSS/First_steps)
* [/vi/docs/Web/JavaScript/Reference/Global_Objects/Promise/prototype](https://developer.mozilla.org/vi/docs/Web/JavaScript/Reference/Global_Objects/Promise/prototype) → [/vi/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Promise](/vi/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Promise)
* [/vi/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators](https://developer.mozilla.org/vi/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators) → [/vi/docs/conflicting/Web/JavaScript/Reference/Operators](/vi/docs/conflicting/Web/JavaScript/Reference/Operators)

### Renamed
* [/vi/docs/Learn/Common_questions/Internet_lam_viec_nh_the_nao](https://developer.mozilla.org/vi/docs/Learn/Common_questions/Internet_lam_viec_nh_the_nao) → [/vi/docs/Learn/Common_questions/How_does_the_Internet_work](/vi/docs/Learn/Common_questions/How_does_the_Internet_work)
* [/vi/docs/Learn/Common_questions/thiet_lap_web_mang_noi_bo](https://developer.mozilla.org/vi/docs/Learn/Common_questions/thiet_lap_web_mang_noi_bo) → [/vi/docs/Learn/Common_questions/set_up_a_local_testing_server](/vi/docs/Learn/Common_questions/set_up_a_local_testing_server)
* [/vi/docs/Learn/Getting_started_with_the_web/Cài_đặt_các_phần_mềm_cơ_bản](https://developer.mozilla.org/vi/docs/Learn/Getting_started_with_the_web/Cài_đặt_các_phần_mềm_cơ_bản) → [/vi/docs/Learn/Getting_started_with_the_web/Installing_basic_software](/vi/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/vi/docs/Learn/HTML/Forms](https://developer.mozilla.org/vi/docs/Learn/HTML/Forms) → [/vi/docs/Learn/Forms](/vi/docs/Learn/Forms)
* [/vi/docs/Tu-dien-thuat-ngu/AJAX](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/AJAX) → [/vi/docs/Glossary/AJAX](/vi/docs/Glossary/AJAX)
* [/vi/docs/Tu-dien-thuat-ngu/Algorithm](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Algorithm) → [/vi/docs/Glossary/Algorithm](/vi/docs/Glossary/Algorithm)
* [/vi/docs/Tu-dien-thuat-ngu/array](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/array) → [/vi/docs/Glossary/array](/vi/docs/Glossary/array)
* [/vi/docs/Tu-dien-thuat-ngu/Attribute](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Attribute) → [/vi/docs/Glossary/Attribute](/vi/docs/Glossary/Attribute)
* [/vi/docs/Tu-dien-thuat-ngu/Bandwidth](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Bandwidth) → [/vi/docs/Glossary/Bandwidth](/vi/docs/Glossary/Bandwidth)
* [/vi/docs/Tu-dien-thuat-ngu/Boolean](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Boolean) → [/vi/docs/Glossary/Boolean](/vi/docs/Glossary/Boolean)
* [/vi/docs/Tu-dien-thuat-ngu/Cache](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Cache) → [/vi/docs/Glossary/Cache](/vi/docs/Glossary/Cache)
* [/vi/docs/Tu-dien-thuat-ngu/Callback_function](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Callback_function) → [/vi/docs/Glossary/Callback_function](/vi/docs/Glossary/Callback_function)
* [/vi/docs/Tu-dien-thuat-ngu/CDN](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/CDN) → [/vi/docs/Glossary/CDN](/vi/docs/Glossary/CDN)
* [/vi/docs/Tu-dien-thuat-ngu/Computer_Programming](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Computer_Programming) → [/vi/docs/Glossary/Computer_Programming](/vi/docs/Glossary/Computer_Programming)
* [/vi/docs/Tu-dien-thuat-ngu/CSS](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/CSS) → [/vi/docs/Glossary/CSS](/vi/docs/Glossary/CSS)
* [/vi/docs/Tu-dien-thuat-ngu/Dynamic_programming_language](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Dynamic_programming_language) → [/vi/docs/Glossary/Dynamic_programming_language](/vi/docs/Glossary/Dynamic_programming_language)
* [/vi/docs/Tu-dien-thuat-ngu/Falsy](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Falsy) → [/vi/docs/Glossary/Falsy](/vi/docs/Glossary/Falsy)
* [/vi/docs/Tu-dien-thuat-ngu/General_header](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/General_header) → [/vi/docs/Glossary/General_header](/vi/docs/Glossary/General_header)
* [/vi/docs/Tu-dien-thuat-ngu/Head](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Head) → [/vi/docs/Glossary/Head](/vi/docs/Glossary/Head)
* [/vi/docs/Tu-dien-thuat-ngu/Hoisting](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Hoisting) → [/vi/docs/Glossary/Hoisting](/vi/docs/Glossary/Hoisting)
* [/vi/docs/Tu-dien-thuat-ngu/HTML](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/HTML) → [/vi/docs/Glossary/HTML](/vi/docs/Glossary/HTML)
* [/vi/docs/Tu-dien-thuat-ngu/Identifier](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Identifier) → [/vi/docs/Glossary/Identifier](/vi/docs/Glossary/Identifier)
* [/vi/docs/Tu-dien-thuat-ngu](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu) → [/vi/docs/Glossary](/vi/docs/Glossary)
* [/vi/docs/Tu-dien-thuat-ngu/jQuery](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/jQuery) → [/vi/docs/Glossary/jQuery](/vi/docs/Glossary/jQuery)
* [/vi/docs/Tu-dien-thuat-ngu/JSON](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/JSON) → [/vi/docs/Glossary/JSON](/vi/docs/Glossary/JSON)
* [/vi/docs/Tu-dien-thuat-ngu/Metadata](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Metadata) → [/vi/docs/Glossary/Metadata](/vi/docs/Glossary/Metadata)
* [/vi/docs/Tu-dien-thuat-ngu/Null](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Null) → [/vi/docs/Glossary/Null](/vi/docs/Glossary/Null)
* [/vi/docs/Tu-dien-thuat-ngu/Operand](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Operand) → [/vi/docs/Glossary/Operand](/vi/docs/Glossary/Operand)
* [/vi/docs/Tu-dien-thuat-ngu/PHP](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/PHP) → [/vi/docs/Glossary/PHP](/vi/docs/Glossary/PHP)
* [/vi/docs/Tu-dien-thuat-ngu/Primitive](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Primitive) → [/vi/docs/Glossary/Primitive](/vi/docs/Glossary/Primitive)
* [/vi/docs/Tu-dien-thuat-ngu/Responsive_web_design](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Responsive_web_design) → [/vi/docs/Glossary/Responsive_web_design](/vi/docs/Glossary/Responsive_web_design)
* [/vi/docs/Tu-dien-thuat-ngu/SVG](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/SVG) → [/vi/docs/Glossary/SVG](/vi/docs/Glossary/SVG)
* [/vi/docs/Tu-dien-thuat-ngu/trinh-duyet](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/trinh-duyet) → [/vi/docs/Glossary/Browser](/vi/docs/Glossary/Browser)
* [/vi/docs/Tu-dien-thuat-ngu/Truthy](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Truthy) → [/vi/docs/Glossary/Truthy](/vi/docs/Glossary/Truthy)
* [/vi/docs/Tu-dien-thuat-ngu/Type_Conversion](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/Type_Conversion) → [/vi/docs/Glossary/Type_Conversion](/vi/docs/Glossary/Type_Conversion)
* [/vi/docs/Tu-dien-thuat-ngu/undefined](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/undefined) → [/vi/docs/Glossary/undefined](/vi/docs/Glossary/undefined)
* [/vi/docs/Tu-dien-thuat-ngu/XML](https://developer.mozilla.org/vi/docs/Tu-dien-thuat-ngu/XML) → [/vi/docs/Glossary/XML](/vi/docs/Glossary/XML)
* [/vi/docs/Web/API/AudioContext/createOscillator](https://developer.mozilla.org/vi/docs/Web/API/AudioContext/createOscillator) → [/vi/docs/Web/API/BaseAudioContext/createOscillator](/vi/docs/Web/API/BaseAudioContext/createOscillator)
* [/vi/docs/Web/API/HTMLElement/dataset](https://developer.mozilla.org/vi/docs/Web/API/HTMLElement/dataset) → [/vi/docs/Web/API/HTMLOrForeignElement/dataset](/vi/docs/Web/API/HTMLOrForeignElement/dataset)
* [/vi/docs/Web/API/Navigator/sendBeacon-vi](https://developer.mozilla.org/vi/docs/Web/API/Navigator/sendBeacon-vi) → [/vi/docs/Web/API/Navigator/sendBeacon](/vi/docs/Web/API/Navigator/sendBeacon)
* [/vi/docs/Web/CSS/CSS_Box_Model/Kien_thuc_co_ban_ve_css_box_model](https://developer.mozilla.org/vi/docs/Web/CSS/CSS_Box_Model/Kien_thuc_co_ban_ve_css_box_model) → [/vi/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model](/vi/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
* [/vi/docs/Web/CSS/CSS_Grid_Layout/tong_quan_ve_grid_layout](https://developer.mozilla.org/vi/docs/Web/CSS/CSS_Grid_Layout/tong_quan_ve_grid_layout) → [/vi/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout](/vi/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout)
* [/vi/docs/Web/Events/load](https://developer.mozilla.org/vi/docs/Web/Events/load) → [/vi/docs/Web/API/Window/load_event](/vi/docs/Web/API/Window/load_event)
* [/vi/docs/Web/JavaScript/Guide/cu-phap-lap-trinh](https://developer.mozilla.org/vi/docs/Web/JavaScript/Guide/cu-phap-lap-trinh) → [/vi/docs/Web/JavaScript/Guide/Grammar_and_types](/vi/docs/Web/JavaScript/Guide/Grammar_and_types)
* [/vi/docs/Web/JavaScript/Guide/Gioi-thieu](https://developer.mozilla.org/vi/docs/Web/JavaScript/Guide/Gioi-thieu) → [/vi/docs/Web/JavaScript/Guide/Introduction](/vi/docs/Web/JavaScript/Guide/Introduction)
* [/vi/docs/Web/JavaScript/Reference/Errors/qua_nhieu_de_quy](https://developer.mozilla.org/vi/docs/Web/JavaScript/Reference/Errors/qua_nhieu_de_quy) → [/vi/docs/Web/JavaScript/Reference/Errors/Too_much_recursion](/vi/docs/Web/JavaScript/Reference/Errors/Too_much_recursion)
* [/vi/docs/Web/JavaScript/Reference/Global_Objects/Array/Sắp_xếp](https://developer.mozilla.org/vi/docs/Web/JavaScript/Reference/Global_Objects/Array/Sắp_xếp) → [/vi/docs/Web/JavaScript/Reference/Global_Objects/Array/sort](/vi/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
* [/vi/docs/Web/JavaScript/Reference/Global_Objects/loi](https://developer.mozilla.org/vi/docs/Web/JavaScript/Reference/Global_Objects/loi) → [/vi/docs/Web/JavaScript/Reference/Global_Objects/Error](/vi/docs/Web/JavaScript/Reference/Global_Objects/Error)
* [/vi/docs/Web/CSS/filter-function/url](https://developer.mozilla.org/vi/docs/Web/CSS/filter-function/url) → [/vi/docs/Web/CSS/url()](/vi/docs/Web/CSS/url())
