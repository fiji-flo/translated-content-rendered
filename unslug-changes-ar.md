# ar

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 269 documents.
* Moved 59 document.
  * 14 orphaned documents.
  * 7 conflicting documents.
  * 38 renamed documents.

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

* [/ar/docs/heesfoord007](https://developer.mozilla.org/ar/docs/heesfoord007) → [/ar/docs/orphaned/heesfoord007](/ar/docs/orphaned/heesfoord007)
* [/ar/docs/Learn/How_to_contribute](https://developer.mozilla.org/ar/docs/Learn/How_to_contribute) → [/ar/docs/orphaned/Learn/How_to_contribute](/ar/docs/orphaned/Learn/How_to_contribute)
* [/ar/docs/MDN/Community](https://developer.mozilla.org/ar/docs/MDN/Community) → [/ar/docs/orphaned/MDN/Community](/ar/docs/orphaned/MDN/Community)
* [/ar/docs/MDN/Community/Whats_happening](https://developer.mozilla.org/ar/docs/MDN/Community/Whats_happening) → [/ar/docs/orphaned/MDN/Community/Whats_happening](/ar/docs/orphaned/MDN/Community/Whats_happening)
* [/ar/docs/MDN/Contribute/Howto/Do_a_technical_review](https://developer.mozilla.org/ar/docs/MDN/Contribute/Howto/Do_a_technical_review) → [/ar/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review](/ar/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review)
* [/ar/docs/MDN/Contribute/Howto/Do_an_editorial_review](https://developer.mozilla.org/ar/docs/MDN/Contribute/Howto/Do_an_editorial_review) → [/ar/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review](/ar/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review)
* [/ar/docs/MDN/Contribute/Howto/Set_the_summary_for_a_page](https://developer.mozilla.org/ar/docs/MDN/Contribute/Howto/Set_the_summary_for_a_page) → [/ar/docs/orphaned/MDN/Contribute/Howto/Set_the_summary_for_a_page](/ar/docs/orphaned/MDN/Contribute/Howto/Set_the_summary_for_a_page)
* [/ar/docs/MDN/Contribute/Howto/Write_an_article_to_help_learn_about_the_Web](https://developer.mozilla.org/ar/docs/MDN/Contribute/Howto/Write_an_article_to_help_learn_about_the_Web) → [/ar/docs/orphaned/MDN/Contribute/Howto/Write_an_article_to_help_learn_about_the_Web](/ar/docs/orphaned/MDN/Contribute/Howto/Write_an_article_to_help_learn_about_the_Web)
* [/ar/docs/MDN/Contribute/Howto/إنشاء_حساب_على_شبكة_مطوري_موزيلا](https://developer.mozilla.org/ar/docs/MDN/Contribute/Howto/إنشاء_حساب_على_شبكة_مطوري_موزيلا) → [/ar/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](/ar/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/ar/docs/MDN/Tools/Deleting_pages](https://developer.mozilla.org/ar/docs/MDN/Tools/Deleting_pages) → [/ar/docs/orphaned/MDN/Tools/Page_deletion](/ar/docs/orphaned/MDN/Tools/Page_deletion)
* [/ar/docs/أحداث_مكتبة_jQuery](https://developer.mozilla.org/ar/docs/أحداث_مكتبة_jQuery) → [/ar/docs/orphaned/أحداث_مكتبة_jQuery](/ar/docs/orphaned/أحداث_مكتبة_jQuery)
* [/ar/docs/مكتبة_جي_كويري](https://developer.mozilla.org/ar/docs/مكتبة_جي_كويري) → [/ar/docs/orphaned/مكتبة_جي_كويري](/ar/docs/orphaned/مكتبة_جي_كويري)
* [/ar/docs/واصفة_SpellCheck_الجديدة_في_HTML5](https://developer.mozilla.org/ar/docs/واصفة_SpellCheck_الجديدة_في_HTML5) → [/ar/docs/orphaned/واصفة_SpellCheck_الجديدة_في_HTML5](/ar/docs/orphaned/واصفة_SpellCheck_الجديدة_في_HTML5)
* [/ar/docs/واصفة_العنوان_في_HTML](https://developer.mozilla.org/ar/docs/واصفة_العنوان_في_HTML) → [/ar/docs/orphaned/واصفة_العنوان_في_HTML](/ar/docs/orphaned/واصفة_العنوان_في_HTML)

### Conflicting
* [/ar/docs/Web/HTML_لغة_ترميز_النص_الفائق](https://developer.mozilla.org/ar/docs/Web/HTML_لغة_ترميز_النص_الفائق) → [/ar/docs/conflicting/Web/HTML](/ar/docs/conflicting/Web/HTML)
* [/ar/docs/Learn/HTML/بسيطة_HTML_إنشاء_صفحة](https://developer.mozilla.org/ar/docs/Learn/HTML/بسيطة_HTML_إنشاء_صفحة) → [/ar/docs/conflicting/Learn/Getting_started_with_the_web](/ar/docs/conflicting/Learn/Getting_started_with_the_web)
* [/ar/docs/Web_Development](https://developer.mozilla.org/ar/docs/Web_Development) → [/ar/docs/conflicting/Web/Guide](/ar/docs/conflicting/Web/Guide)
* [/ar/docs/Web/Guide/CSS/Getting_started](https://developer.mozilla.org/ar/docs/Web/Guide/CSS/Getting_started) → [/ar/docs/conflicting/Learn/CSS/First_steps](/ar/docs/conflicting/Learn/CSS/First_steps)
* [/ar/docs/Web/Guide/CSS](https://developer.mozilla.org/ar/docs/Web/Guide/CSS) → [/ar/docs/conflicting/Learn/CSS](/ar/docs/conflicting/Learn/CSS)
* [/ar/docs/Web/Guide/HTML/HTML5/HTML5_element_list](https://developer.mozilla.org/ar/docs/Web/Guide/HTML/HTML5/HTML5_element_list) → [/ar/docs/conflicting/Web/HTML/Element](/ar/docs/conflicting/Web/HTML/Element)
* [/ar/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript](https://developer.mozilla.org/ar/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript) → [/ar/docs/conflicting/Learn/JavaScript/Objects](/ar/docs/conflicting/Learn/JavaScript/Objects)

### Renamed
* [/ar/docs/Glossary/الحروف](https://developer.mozilla.org/ar/docs/Glossary/الحروف) → [/ar/docs/Glossary/Character](/ar/docs/Glossary/Character)
* [/ar/docs/Glossary/الخاصية](https://developer.mozilla.org/ar/docs/Glossary/الخاصية) → [/ar/docs/Glossary/property](/ar/docs/Glossary/property)
* [/ar/docs/Glossary/الدوال_من_الدرجة_الأولى](https://developer.mozilla.org/ar/docs/Glossary/الدوال_من_الدرجة_الأولى) → [/ar/docs/Glossary/First-class_Function](/ar/docs/Glossary/First-class_Function)
* [/ar/docs/Glossary/الكائنات](https://developer.mozilla.org/ar/docs/Glossary/الكائنات) → [/ar/docs/Glossary/Object](/ar/docs/Glossary/Object)
* [/ar/docs/Glossary/المجالات](https://developer.mozilla.org/ar/docs/Glossary/المجالات) → [/ar/docs/Glossary/Scope](/ar/docs/Glossary/Scope)
* [/ar/docs/HTML/Element/article](https://developer.mozilla.org/ar/docs/HTML/Element/article) → [/ar/docs/Web/HTML/Element/article](/ar/docs/Web/HTML/Element/article)
* [/ar/docs/HTML/Element/bdo](https://developer.mozilla.org/ar/docs/HTML/Element/bdo) → [/ar/docs/Web/HTML/Element/bdo](/ar/docs/Web/HTML/Element/bdo)
* [/ar/docs/HTML/Element/headings_elements](https://developer.mozilla.org/ar/docs/HTML/Element/headings_elements) → [/ar/docs/Web/HTML/Element/Heading_Elements](/ar/docs/Web/HTML/Element/Heading_Elements)
* [/ar/docs/HTML/Element](https://developer.mozilla.org/ar/docs/HTML/Element) → [/ar/docs/Web/HTML/Element](/ar/docs/Web/HTML/Element)
* [/ar/docs/HTML/Element/span](https://developer.mozilla.org/ar/docs/HTML/Element/span) → [/ar/docs/Web/HTML/Element/span](/ar/docs/Web/HTML/Element/span)
* [/ar/docs/HTML/Element/tt](https://developer.mozilla.org/ar/docs/HTML/Element/tt) → [/ar/docs/Web/HTML/Element/tt](/ar/docs/Web/HTML/Element/tt)
* [/ar/docs/Learn/Common_questions/كيفية_عمل](https://developer.mozilla.org/ar/docs/Learn/Common_questions/كيفية_عمل) → [/ar/docs/Learn/Common_questions/How_does_the_Internet_work](/ar/docs/Learn/Common_questions/How_does_the_Internet_work)
* [/ar/docs/Learn/Getting_started_with_the_web/أساسيات_صفحات_الطرز_المتراصة](https://developer.mozilla.org/ar/docs/Learn/Getting_started_with_the_web/أساسيات_صفحات_الطرز_المتراصة) → [/ar/docs/Learn/Getting_started_with_the_web/CSS_basics](/ar/docs/Learn/Getting_started_with_the_web/CSS_basics)
* [/ar/docs/Learn/HTML/Forms](https://developer.mozilla.org/ar/docs/Learn/HTML/Forms) → [/ar/docs/Learn/Forms](/ar/docs/Learn/Forms)
* [/ar/docs/Learn/HTML/الجداول](https://developer.mozilla.org/ar/docs/Learn/HTML/الجداول) → [/ar/docs/Learn/HTML/Tables](/ar/docs/Learn/HTML/Tables)
* [/ar/docs/MDN_at_ten](https://developer.mozilla.org/ar/docs/MDN_at_ten) → [/ar/docs/MDN/At_ten](/ar/docs/MDN/At_ten)
* [/ar/docs/MDN/Contribute/Howto/كيفية_إنشاء_وتحرير_الصفحات](https://developer.mozilla.org/ar/docs/MDN/Contribute/Howto/كيفية_إنشاء_وتحرير_الصفحات) → [/ar/docs/MDN/Contribute/Howto/Create_and_edit_pages](/ar/docs/MDN/Contribute/Howto/Create_and_edit_pages)
* [/ar/docs/MDN/Kuma](https://developer.mozilla.org/ar/docs/MDN/Kuma) → [/ar/docs/MDN/Yari](/ar/docs/MDN/Yari)
* [/ar/docs/Mozilla/Add-ons/WebExtensions/ما_هي_امتدادات_الويب](https://developer.mozilla.org/ar/docs/Mozilla/Add-ons/WebExtensions/ما_هي_امتدادات_الويب) → [/ar/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions](/ar/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions)
* [/ar/docs/Web/API/Geolocation/Using_geolocation](https://developer.mozilla.org/ar/docs/Web/API/Geolocation/Using_geolocation) → [/ar/docs/Web/API/Geolocation_API](/ar/docs/Web/API/Geolocation_API)
* [/ar/docs/Web/API/Geolocation/Using_geolocation/Using_the_Geolocation_API](https://developer.mozilla.org/ar/docs/Web/API/Geolocation/Using_geolocation/Using_the_Geolocation_API) → [/ar/docs/Web/API/Geolocation_API/Using_the_Geolocation_API](/ar/docs/Web/API/Geolocation_API/Using_the_Geolocation_API)
* [/ar/docs/Web/API/History_API/مثال](https://developer.mozilla.org/ar/docs/Web/API/History_API/مثال) → [/ar/docs/Web/API/History_API/Example](/ar/docs/Web/API/History_API/Example)
* [/ar/docs/Web/API/Navigator.battery](https://developer.mozilla.org/ar/docs/Web/API/Navigator.battery) → [/ar/docs/Web/API/Navigator/battery](/ar/docs/Web/API/Navigator/battery)
* [/ar/docs/Web/CSS/CSS_Flexible_Box_Layout/المفاهيم_الأساسية_للصندوق_المرن](https://developer.mozilla.org/ar/docs/Web/CSS/CSS_Flexible_Box_Layout/المفاهيم_الأساسية_للصندوق_المرن) → [/ar/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox](/ar/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
* [/ar/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout_arabic](https://developer.mozilla.org/ar/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout_arabic) → [/ar/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout](/ar/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout)
* [/ar/docs/Web/CSS/التحول](https://developer.mozilla.org/ar/docs/Web/CSS/التحول) → [/ar/docs/Web/CSS/transform](/ar/docs/Web/CSS/transform)
* [/ar/docs/Web/CSS/التعليقات](https://developer.mozilla.org/ar/docs/Web/CSS/التعليقات) → [/ar/docs/Web/CSS/Comments](/ar/docs/Web/CSS/Comments)
* [/ar/docs/Web/CSS/العناصر_التي_يمكن_تحريكها_باستخدام_CSS_Transitions](https://developer.mozilla.org/ar/docs/Web/CSS/العناصر_التي_يمكن_تحريكها_باستخدام_CSS_Transitions) → [/ar/docs/Web/CSS/CSS_animated_properties](/ar/docs/Web/CSS/CSS_animated_properties)
* [/ar/docs/Web/Guide/الرسومات](https://developer.mozilla.org/ar/docs/Web/Guide/الرسومات) → [/ar/docs/Web/Guide/Graphics](/ar/docs/Web/Guide/Graphics)
* [/ar/docs/Web/JavaScript/Guide/الدوال](https://developer.mozilla.org/ar/docs/Web/JavaScript/Guide/الدوال) → [/ar/docs/Web/JavaScript/Guide/Functions](/ar/docs/Web/JavaScript/Guide/Functions)
* [/ar/docs/Web/JavaScript/Reference/Global_Objects/الارقام](https://developer.mozilla.org/ar/docs/Web/JavaScript/Reference/Global_Objects/الارقام) → [/ar/docs/Web/JavaScript/Reference/Global_Objects/Number](/ar/docs/Web/JavaScript/Reference/Global_Objects/Number)
* [/ar/docs/Web/JavaScript/Reference/الدوال/get](https://developer.mozilla.org/ar/docs/Web/JavaScript/Reference/الدوال/get) → [/ar/docs/Web/JavaScript/Reference/Functions/get](/ar/docs/Web/JavaScript/Reference/Functions/get)
* [/ar/docs/Web/JavaScript/Reference/الدوال](https://developer.mozilla.org/ar/docs/Web/JavaScript/Reference/الدوال) → [/ar/docs/Web/JavaScript/Reference/Functions](/ar/docs/Web/JavaScript/Reference/Functions)
* [/ar/docs/Web/حماية](https://developer.mozilla.org/ar/docs/Web/حماية) → [/ar/docs/Web/Security](/ar/docs/Web/Security)
* [/ar/docs/Web/مرجع.](https://developer.mozilla.org/ar/docs/Web/مرجع.) → [/ar/docs/Web/Reference](/ar/docs/Web/Reference)
* [/ar/docs/Web_Development/Mobile](https://developer.mozilla.org/ar/docs/Web_Development/Mobile) → [/ar/docs/Web/Guide/Mobile](/ar/docs/Web/Guide/Mobile)
* [/ar/docs/Web/Guide/CSS/Getting_started/Readable_CSS](https://developer.mozilla.org/ar/docs/Web/Guide/CSS/Getting_started/Readable_CSS) → [/ar/docs/Learn/CSS/First_steps/How_CSS_is_structured](/ar/docs/Learn/CSS/First_steps/How_CSS_is_structured)
* [/ar/docs/Web/Guide/CSS/Getting_started/القوائم](https://developer.mozilla.org/ar/docs/Web/Guide/CSS/Getting_started/القوائم) → [/ar/docs/Learn/CSS/Styling_text/Styling_lists](/ar/docs/Learn/CSS/Styling_text/Styling_lists)
