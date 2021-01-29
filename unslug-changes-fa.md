# fa

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 148 documents.
* Moved 31 document.
  * 5 orphaned documents.
  * 2 conflicting documents.
  * 24 renamed documents.

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

* [/fa/docs/MDN/Community](https://developer.mozilla.org/fa/docs/MDN/Community) → [/fa/docs/orphaned/MDN/Community](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/orphaned/MDN/Community)
* [/fa/docs/MDN/Contribute/Howto/Be_a_beta_tester](https://developer.mozilla.org/fa/docs/MDN/Contribute/Howto/Be_a_beta_tester) → [/fa/docs/orphaned/MDN/Contribute/Howto/Be_a_beta_tester](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/orphaned/MDN/Contribute/Howto/Be_a_beta_tester)
* [/fa/docs/MDN/Contribute/Howto/ساختنـحسابـکاربری](https://developer.mozilla.org/fa/docs/MDN/Contribute/Howto/ساختنـحسابـکاربری) → [/fa/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/fa/docs/Web/جاوااسکریپت](https://developer.mozilla.org/fa/docs/Web/جاوااسکریپت) → [/fa/docs/orphaned/Web/جاوااسکریپت](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/orphaned/Web/جاوااسکریپت)
* [/fa/docs/توسعه_وب](https://developer.mozilla.org/fa/docs/توسعه_وب) → [/fa/docs/orphaned/توسعه_وب](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/orphaned/توسعه_وب)

### Conflicting
* [/fa/docs/Web_development/Historical_artifacts_to_avoid](https://developer.mozilla.org/fa/docs/Web_development/Historical_artifacts_to_avoid) → [/fa/docs/conflicting/Learn/HTML/Introduction_to_HTML](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/conflicting/Learn/HTML/Introduction_to_HTML)
* [/fa/docs/Web_Development](https://developer.mozilla.org/fa/docs/Web_Development) → [/fa/docs/conflicting/Web/Guide](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/conflicting/Web/Guide)

### Renamed
* [/fa/docs/HTML/Attributes](https://developer.mozilla.org/fa/docs/HTML/Attributes) → [/fa/docs/Web/HTML/Attributes](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/HTML/Attributes)
* [/fa/docs/HTML/HTML5](https://developer.mozilla.org/fa/docs/HTML/HTML5) → [/fa/docs/Web/Guide/HTML/HTML5](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/Guide/HTML/HTML5)
* [/fa/docs/Learn/Getting_started_with_the_web/مقدمات_جاوااسکریپت](https://developer.mozilla.org/fa/docs/Learn/Getting_started_with_the_web/مقدمات_جاوااسکریپت) → [/fa/docs/Learn/Getting_started_with_the_web/JavaScript_basics](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
* [/fa/docs/Learn/Getting_started_with_the_web/منتشر_کردن_وبسایت_شما](https://developer.mozilla.org/fa/docs/Learn/Getting_started_with_the_web/منتشر_کردن_وبسایت_شما) → [/fa/docs/Learn/Getting_started_with_the_web/Publishing_your_website](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/Getting_started_with_the_web/Publishing_your_website)
* [/fa/docs/Learn/Getting_started_with_the_web/نصب_نرم_افزارهای_پایه](https://developer.mozilla.org/fa/docs/Learn/Getting_started_with_the_web/نصب_نرم_افزارهای_پایه) → [/fa/docs/Learn/Getting_started_with_the_web/Installing_basic_software](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/fa/docs/Learn/Getting_started_with_the_web/وب_سایت_شما_چه_شکلی_است؟](https://developer.mozilla.org/fa/docs/Learn/Getting_started_with_the_web/وب_سایت_شما_چه_شکلی_است؟) → [/fa/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
* [/fa/docs/Learn/JavaScript/Objects/مقدمات](https://developer.mozilla.org/fa/docs/Learn/JavaScript/Objects/مقدمات) → [/fa/docs/Learn/JavaScript/Objects/Basics](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/JavaScript/Objects/Basics)
* [/fa/docs/Learn/Server-side/قدم_اول](https://developer.mozilla.org/fa/docs/Learn/Server-side/قدم_اول) → [/fa/docs/Learn/Server-side/First_steps](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/Server-side/First_steps)
* [/fa/docs/MDN_at_ten](https://developer.mozilla.org/fa/docs/MDN_at_ten) → [/fa/docs/MDN/At_ten](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/MDN/At_ten)
* [/fa/docs/Server-sent_events](https://developer.mozilla.org/fa/docs/Server-sent_events) → [/fa/docs/Web/API/Server-sent_events](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/API/Server-sent_events)
* [/fa/docs/Web/API/Node/innerText](https://developer.mozilla.org/fa/docs/Web/API/Node/innerText) → [/fa/docs/Web/API/HTMLElement/innerText](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/API/HTMLElement/innerText)
* [/fa/docs/Web/CSS/Media_Queries/ابزار-تست-رسانه-پاسخگو](https://developer.mozilla.org/fa/docs/Web/CSS/Media_Queries/ابزار-تست-رسانه-پاسخگو) → [/fa/docs/Web/CSS/Media_Queries/Using_media_queries](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/CSS/Media_Queries/Using_media_queries)
* [/fa/docs/Web/CSS/انتخابگرـنوع](https://developer.mozilla.org/fa/docs/Web/CSS/انتخابگرـنوع) → [/fa/docs/Web/CSS/Type_selectors](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/CSS/Type_selectors)
* [/fa/docs/Web/CSS/انتخابگرـویژگی](https://developer.mozilla.org/fa/docs/Web/CSS/انتخابگرـویژگی) → [/fa/docs/Web/CSS/Attribute_selectors](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/CSS/Attribute_selectors)
* [/fa/docs/Web/CSS/بزرگنمایی](https://developer.mozilla.org/fa/docs/Web/CSS/بزرگنمایی) → [/fa/docs/Web/CSS/zoom](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/CSS/zoom)
* [/fa/docs/Web/HTML/Tips_for_authoring_fast-loading_HTML_pages](https://developer.mozilla.org/fa/docs/Web/HTML/Tips_for_authoring_fast-loading_HTML_pages) → [/fa/docs/Learn/HTML/Howto/Author_fast-loading_HTML_pages](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Learn/HTML/Howto/Author_fast-loading_HTML_pages)
* [/fa/docs/Web/HTML/افزودن_رنگ](https://developer.mozilla.org/fa/docs/Web/HTML/افزودن_رنگ) → [/fa/docs/Web/HTML/Applying_color](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/HTML/Applying_color)
* [/fa/docs/Web/JavaScript/راهنما/Control_flow_and_error_handling](https://developer.mozilla.org/fa/docs/Web/JavaScript/راهنما/Control_flow_and_error_handling) → [/fa/docs/Web/JavaScript/Guide/Control_flow_and_error_handling](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
* [/fa/docs/Web/JavaScript/راهنما/Details_of_the_Object_Model](https://developer.mozilla.org/fa/docs/Web/JavaScript/راهنما/Details_of_the_Object_Model) → [/fa/docs/Web/JavaScript/Guide/Details_of_the_Object_Model](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/JavaScript/Guide/Details_of_the_Object_Model)
* [/fa/docs/Web/JavaScript/راهنما/Functions](https://developer.mozilla.org/fa/docs/Web/JavaScript/راهنما/Functions) → [/fa/docs/Web/JavaScript/Guide/Functions](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/JavaScript/Guide/Functions)
* [/fa/docs/Web/JavaScript/راهنما/Grammar_and_types](https://developer.mozilla.org/fa/docs/Web/JavaScript/راهنما/Grammar_and_types) → [/fa/docs/Web/JavaScript/Guide/Grammar_and_types](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/JavaScript/Guide/Grammar_and_types)
* [/fa/docs/Web/JavaScript/راهنما](https://developer.mozilla.org/fa/docs/Web/JavaScript/راهنما) → [/fa/docs/Web/JavaScript/Guide](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/JavaScript/Guide)
* [/fa/docs/Web/JavaScript/راهنما/مقدمه](https://developer.mozilla.org/fa/docs/Web/JavaScript/راهنما/مقدمه) → [/fa/docs/Web/JavaScript/Guide/Introduction](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/JavaScript/Guide/Introduction)
* [/fa/docs/HTML/Canvas/Drawing_Graphics_with_Canvas](https://developer.mozilla.org/fa/docs/HTML/Canvas/Drawing_Graphics_with_Canvas) → [/fa/docs/Web/API/Canvas_API/Tutorial](https://unslug-next.content.dev.mdn.mozit.cloud/fa/docs/Web/API/Canvas_API/Tutorial)
