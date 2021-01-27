# nl

This is the summary of moving to english slugs only and enforcing the same
document hierarchy for all locales. This requires every translated document to
have exactly one corresponding english document with the same slug.

## Summary

* Total of 286 documents.
* Moved 74 document.
  * 12 orphaned documents.
  * 3 conflicting documents.
  * 59 renamed documents.

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

* [/nl/docs/MDN/Community/Conversations](https://developer.mozilla.org/nl/docs/MDN/Community/Conversations) → [/nl/docs/orphaned/MDN/Community/Conversations](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Community/Conversations)
* [/nl/docs/MDN/Community](https://developer.mozilla.org/nl/docs/MDN/Community) → [/nl/docs/orphaned/MDN/Community](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Community)
* [/nl/docs/MDN/Community/Samenwerken_in_een_community](https://developer.mozilla.org/nl/docs/MDN/Community/Samenwerken_in_een_community) → [/nl/docs/orphaned/MDN/Community/Working_in_community](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Community/Working_in_community)
* [/nl/docs/MDN/Community/Whats_happening](https://developer.mozilla.org/nl/docs/MDN/Community/Whats_happening) → [/nl/docs/orphaned/MDN/Community/Whats_happening](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Community/Whats_happening)
* [/nl/docs/MDN/Contribute/Howto/Aanmaken_MDN_account](https://developer.mozilla.org/nl/docs/MDN/Contribute/Howto/Aanmaken_MDN_account) → [/nl/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Contribute/Howto/Create_an_MDN_account)
* [/nl/docs/MDN/Contribute/Howto/Een_redactionele_beoordeling_geven](https://developer.mozilla.org/nl/docs/MDN/Contribute/Howto/Een_redactionele_beoordeling_geven) → [/nl/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Contribute/Howto/Do_an_editorial_review)
* [/nl/docs/MDN/Contribute/Howto/Een_technische_beoordeling_maken](https://developer.mozilla.org/nl/docs/MDN/Contribute/Howto/Een_technische_beoordeling_maken) → [/nl/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Contribute/Howto/Do_a_technical_review)
* [/nl/docs/MDN/Contribute/Howto/Taggen_JavaScript_pagina](https://developer.mozilla.org/nl/docs/MDN/Contribute/Howto/Taggen_JavaScript_pagina) → [/nl/docs/orphaned/MDN/Contribute/Howto/Tag_JavaScript_pages](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Contribute/Howto/Tag_JavaScript_pages)
* [/nl/docs/MDN/Contribute/Processes/Verhoogde_bevoegdheden_aanvragen](https://developer.mozilla.org/nl/docs/MDN/Contribute/Processes/Verhoogde_bevoegdheden_aanvragen) → [/nl/docs/orphaned/MDN/Contribute/Processes/Requesting_elevated_privileges](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Contribute/Processes/Requesting_elevated_privileges)
* [/nl/docs/MDN/Tools/Template_editing](https://developer.mozilla.org/nl/docs/MDN/Tools/Template_editing) → [/nl/docs/orphaned/MDN/Tools/Template_editing](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/MDN/Tools/Template_editing)
* [/nl/docs/Mozilla_Implementeren](https://developer.mozilla.org/nl/docs/Mozilla_Implementeren) → [/nl/docs/orphaned/Mozilla_Implementeren](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/Mozilla_Implementeren)
* [/nl/docs/Mozilla/Add-ons/WebExtensions/Een_verouderde_Firefox-add-on_porteren](https://developer.mozilla.org/nl/docs/Mozilla/Add-ons/WebExtensions/Een_verouderde_Firefox-add-on_porteren) → [/nl/docs/orphaned/Mozilla/Add-ons/WebExtensions/Porting_a_legacy_Firefox_add-on](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/orphaned/Mozilla/Add-ons/WebExtensions/Porting_a_legacy_Firefox_add-on)

### Conflicting
* [/nl/docs/DOM](https://developer.mozilla.org/nl/docs/DOM) → [/nl/docs/conflicting/Web/API/Document_Object_Model](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/conflicting/Web/API/Document_Object_Model)
* [/nl/docs/Web/JavaScript/Aan_de_slag](https://developer.mozilla.org/nl/docs/Web/JavaScript/Aan_de_slag) → [/nl/docs/conflicting/Learn/Getting_started_with_the_web/JavaScript_basics](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/conflicting/Learn/Getting_started_with_the_web/JavaScript_basics)
* [/nl/docs/Web/JavaScript/Reference/Global_Objects/Object/prototype](https://developer.mozilla.org/nl/docs/Web/JavaScript/Reference/Global_Objects/Object/prototype) → [/nl/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Object](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/conflicting/Web/JavaScript/Reference/Global_Objects/Object)

### Renamed
* [/nl/docs/Compatibiliteitstabel_voor_formulierelementen](https://developer.mozilla.org/nl/docs/Compatibiliteitstabel_voor_formulierelementen) → [/nl/docs/Learn/Forms/Property_compatibility_table_for_form_controls](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/Property_compatibility_table_for_form_controls)
* [/nl/docs/Firefox_1.5_voor_ontwikkelaars](https://developer.mozilla.org/nl/docs/Firefox_1.5_voor_ontwikkelaars) → [/nl/docs/Mozilla/Firefox/Releases/1.5](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Mozilla/Firefox/Releases/1.5)
* [/nl/docs/Gebruik_maken_van_DOM_workers](https://developer.mozilla.org/nl/docs/Gebruik_maken_van_DOM_workers) → [/nl/docs/Web/API/Web_Workers_API/Using_web_workers](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/API/Web_Workers_API/Using_web_workers)
* [/nl/docs/Glossary/Abstractie](https://developer.mozilla.org/nl/docs/Glossary/Abstractie) → [/nl/docs/Glossary/Abstraction](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/Abstraction)
* [/nl/docs/Glossary/Asynchroon](https://developer.mozilla.org/nl/docs/Glossary/Asynchroon) → [/nl/docs/Glossary/Asynchronous](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/Asynchronous)
* [/nl/docs/Glossary/Leeg_element](https://developer.mozilla.org/nl/docs/Glossary/Leeg_element) → [/nl/docs/Glossary/Empty_element](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/Empty_element)
* [/nl/docs/Glossary/Sleutelwoord](https://developer.mozilla.org/nl/docs/Glossary/Sleutelwoord) → [/nl/docs/Glossary/Keyword](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/Keyword)
* [/nl/docs/Glossary/SSL_Woordenlijst](https://developer.mozilla.org/nl/docs/Glossary/SSL_Woordenlijst) → [/nl/docs/Glossary/SSL](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/SSL)
* [/nl/docs/Glossary/Toegankelijkheid](https://developer.mozilla.org/nl/docs/Glossary/Toegankelijkheid) → [/nl/docs/Glossary/Accessibility](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/Accessibility)
* [/nl/docs/Glossary/Waarachtig](https://developer.mozilla.org/nl/docs/Glossary/Waarachtig) → [/nl/docs/Glossary/Truthy](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Glossary/Truthy)
* [/nl/docs/Learn/CSS/CSS_layout/Positionering](https://developer.mozilla.org/nl/docs/Learn/CSS/CSS_layout/Positionering) → [/nl/docs/Learn/CSS/CSS_layout/Positioning](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/CSS/CSS_layout/Positioning)
* [/nl/docs/Learn/Getting_started_with_the_web/Basis_software_installeren](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/Basis_software_installeren) → [/nl/docs/Learn/Getting_started_with_the_web/Installing_basic_software](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
* [/nl/docs/Learn/Getting_started_with_the_web/Bestanden_beheren](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/Bestanden_beheren) → [/nl/docs/Learn/Getting_started_with_the_web/Dealing_with_files](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/Dealing_with_files)
* [/nl/docs/Learn/Getting_started_with_the_web/CSS_basisbegrippen](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/CSS_basisbegrippen) → [/nl/docs/Learn/Getting_started_with_the_web/CSS_basics](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/CSS_basics)
* [/nl/docs/Learn/Getting_started_with_the_web/Hoe_gaat_jouw_website_er_uit_zien](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/Hoe_gaat_jouw_website_er_uit_zien) → [/nl/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
* [/nl/docs/Learn/Getting_started_with_the_web/Hoe_werkt_het_web](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/Hoe_werkt_het_web) → [/nl/docs/Learn/Getting_started_with_the_web/How_the_Web_works](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
* [/nl/docs/Learn/Getting_started_with_the_web/HTML_basisbegrippen](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/HTML_basisbegrippen) → [/nl/docs/Learn/Getting_started_with_the_web/HTML_basics](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/HTML_basics)
* [/nl/docs/Learn/Getting_started_with_the_web/Publicatie_website](https://developer.mozilla.org/nl/docs/Learn/Getting_started_with_the_web/Publicatie_website) → [/nl/docs/Learn/Getting_started_with_the_web/Publishing_your_website](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Getting_started_with_the_web/Publishing_your_website)
* [/nl/docs/Learn/HTML/Forms/Geavanceerde_styling_van_HTML-formulieren](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms/Geavanceerde_styling_van_HTML-formulieren) → [/nl/docs/Learn/Forms/Advanced_form_styling](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/Advanced_form_styling)
* [/nl/docs/Learn/HTML/Forms/How_to_structure_an_HTML_form](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms/How_to_structure_an_HTML_form) → [/nl/docs/Learn/Forms/How_to_structure_a_web_form](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/How_to_structure_a_web_form)
* [/nl/docs/Learn/HTML/Forms](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms) → [/nl/docs/Learn/Forms](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms)
* [/nl/docs/Learn/HTML/Forms/Styling_HTML_forms](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms/Styling_HTML_forms) → [/nl/docs/Learn/Forms/Styling_web_forms](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/Styling_web_forms)
* [/nl/docs/Learn/HTML/Forms/The_native_form_widgets](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms/The_native_form_widgets) → [/nl/docs/Learn/Forms/Basic_native_form_controls](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/Basic_native_form_controls)
* [/nl/docs/Learn/HTML/Forms/Verzenden_van_formuliergegevens](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms/Verzenden_van_formuliergegevens) → [/nl/docs/Learn/Forms/Sending_and_retrieving_form_data](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/Sending_and_retrieving_form_data)
* [/nl/docs/Learn/HTML/Forms/Your_first_HTML_form](https://developer.mozilla.org/nl/docs/Learn/HTML/Forms/Your_first_HTML_form) → [/nl/docs/Learn/Forms/Your_first_form](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/Forms/Your_first_form)
* [/nl/docs/Learn/HTML/Introduction_to_HTML/Gevorderde_tekstopmaak](https://developer.mozilla.org/nl/docs/Learn/HTML/Introduction_to_HTML/Gevorderde_tekstopmaak) → [/nl/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
* [/nl/docs/Learn/HTML/Introduction_to_HTML/Het_hoofd_metadata_in_HTML](https://developer.mozilla.org/nl/docs/Learn/HTML/Introduction_to_HTML/Het_hoofd_metadata_in_HTML) → [/nl/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)
* [/nl/docs/Learn/HTML/Introduction_to_HTML/HTML_Debuggen](https://developer.mozilla.org/nl/docs/Learn/HTML/Introduction_to_HTML/HTML_Debuggen) → [/nl/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)
* [/nl/docs/Learn/HTML/Introduction_to_HTML/Hyperlinks_maken](https://developer.mozilla.org/nl/docs/Learn/HTML/Introduction_to_HTML/Hyperlinks_maken) → [/nl/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)
* [/nl/docs/Learn/HTML/Introduction_to_HTML/Opmaak_van_een_brief](https://developer.mozilla.org/nl/docs/Learn/HTML/Introduction_to_HTML/Opmaak_van_een_brief) → [/nl/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter)
* [/nl/docs/Learn/HTML/Introduction_to_HTML/Structureren_inhoud_van_webpagina](https://developer.mozilla.org/nl/docs/Learn/HTML/Introduction_to_HTML/Structureren_inhoud_van_webpagina) → [/nl/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content)
* [/nl/docs/Learn/HTML/Multimedia_inbedden/Afbeeldingen_in_HTML](https://developer.mozilla.org/nl/docs/Learn/HTML/Multimedia_inbedden/Afbeeldingen_in_HTML) → [/nl/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
* [/nl/docs/Learn/HTML/Multimedia_inbedden](https://developer.mozilla.org/nl/docs/Learn/HTML/Multimedia_inbedden) → [/nl/docs/Learn/HTML/Multimedia_and_embedding](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Multimedia_and_embedding)
* [/nl/docs/Learn/JavaScript/Client-side_web_APIs/Manipuleren_documenten](https://developer.mozilla.org/nl/docs/Learn/JavaScript/Client-side_web_APIs/Manipuleren_documenten) → [/nl/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents)
* [/nl/docs/MDN_at_ten](https://developer.mozilla.org/nl/docs/MDN_at_ten) → [/nl/docs/MDN/At_ten](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/MDN/At_ten)
* [/nl/docs/MDN/Guidelines/Style_guide](https://developer.mozilla.org/nl/docs/MDN/Guidelines/Style_guide) → [/nl/docs/MDN/Guidelines/Writing_style_guide](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/MDN/Guidelines/Writing_style_guide)
* [/nl/docs/MDN/Kuma](https://developer.mozilla.org/nl/docs/MDN/Kuma) → [/nl/docs/MDN/Yari](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/MDN/Yari)
* [/nl/docs/MDN/Kuma/Probleemoplossingen_KumaScript_errors](https://developer.mozilla.org/nl/docs/MDN/Kuma/Probleemoplossingen_KumaScript_errors) → [/nl/docs/MDN/Tools/KumaScript/Troubleshooting](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/MDN/Tools/KumaScript/Troubleshooting)
* [/nl/docs/MDN/Over](https://developer.mozilla.org/nl/docs/MDN/Over) → [/nl/docs/MDN/About](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/MDN/About)
* [/nl/docs/Mozilla/Add-ons/WebExtensions/Wat_zijn_WebExtensions](https://developer.mozilla.org/nl/docs/Mozilla/Add-ons/WebExtensions/Wat_zijn_WebExtensions) → [/nl/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions)
* [/nl/docs/Mozilla/Developer_guide/Dus_je_hebt_Firefox_net_gebuild](https://developer.mozilla.org/nl/docs/Mozilla/Developer_guide/Dus_je_hebt_Firefox_net_gebuild) → [/nl/docs/Mozilla/Developer_guide/So_you_just_built_Firefox](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Mozilla/Developer_guide/So_you_just_built_Firefox)
* [/nl/docs/Tools/Responsive_Design_View](https://developer.mozilla.org/nl/docs/Tools/Responsive_Design_View) → [/nl/docs/Tools/Responsive_Design_Mode](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Tools/Responsive_Design_Mode)
* [/nl/docs/Tools/Sneltoetsen](https://developer.mozilla.org/nl/docs/Tools/Sneltoetsen) → [/nl/docs/Tools/Keyboard_shortcuts](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Tools/Keyboard_shortcuts)
* [/nl/docs/Tools/Web_Console/Sneltoetsen](https://developer.mozilla.org/nl/docs/Tools/Web_Console/Sneltoetsen) → [/nl/docs/Tools/Web_Console/Keyboard_shortcuts](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Tools/Web_Console/Keyboard_shortcuts)
* [/nl/docs/Web/API/window.crypto.getRandomValues](https://developer.mozilla.org/nl/docs/Web/API/window.crypto.getRandomValues) → [/nl/docs/Web/API/Crypto/getRandomValues](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/API/Crypto/getRandomValues)
* [/nl/docs/Web/CSS/CSS_Positioning/Understanding_z_index/De_stapelcontext](https://developer.mozilla.org/nl/docs/Web/CSS/CSS_Positioning/Understanding_z_index/De_stapelcontext) → [/nl/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context)
* [/nl/docs/Web/Events/mousedown](https://developer.mozilla.org/nl/docs/Web/Events/mousedown) → [/nl/docs/Web/API/Element/mousedown_event](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/API/Element/mousedown_event)
* [/nl/docs/Web/Events/mouseout](https://developer.mozilla.org/nl/docs/Web/Events/mouseout) → [/nl/docs/Web/API/Element/mouseout_event](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/API/Element/mouseout_event)
* [/nl/docs/Web/JavaScript/Guide/Reguliere_Expressies](https://developer.mozilla.org/nl/docs/Web/JavaScript/Guide/Reguliere_Expressies) → [/nl/docs/Web/JavaScript/Guide/Regular_Expressions](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/JavaScript/Guide/Regular_Expressions)
* [/nl/docs/Web/JavaScript/Guide/Werken_met_objecten](https://developer.mozilla.org/nl/docs/Web/JavaScript/Guide/Werken_met_objecten) → [/nl/docs/Web/JavaScript/Guide/Working_with_Objects](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/JavaScript/Guide/Working_with_Objects)
* [/nl/docs/Web/JavaScript/Reference/Global_Objects/Symbool](https://developer.mozilla.org/nl/docs/Web/JavaScript/Reference/Global_Objects/Symbool) → [/nl/docs/Web/JavaScript/Reference/Global_Objects/Symbol](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
* [/nl/docs/Web/JavaScript/Reference/Klasses](https://developer.mozilla.org/nl/docs/Web/JavaScript/Reference/Klasses) → [/nl/docs/Web/JavaScript/Reference/Classes](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/JavaScript/Reference/Classes)
* [/nl/docs/Web/JavaScript/Reference/Operatoren](https://developer.mozilla.org/nl/docs/Web/JavaScript/Reference/Operatoren) → [/nl/docs/Web/JavaScript/Reference/Operators](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/JavaScript/Reference/Operators)
* [/nl/docs/Web/JavaScript/Reference/Operatoren/typeof](https://developer.mozilla.org/nl/docs/Web/JavaScript/Reference/Operatoren/typeof) → [/nl/docs/Web/JavaScript/Reference/Operators/typeof](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/JavaScript/Reference/Operators/typeof)
* [/nl/docs/Web/SVG/Tutorial/Basis_Transformaties](https://developer.mozilla.org/nl/docs/Web/SVG/Tutorial/Basis_Transformaties) → [/nl/docs/Web/SVG/Tutorial/Basic_Transformations](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/SVG/Tutorial/Basic_Transformations)
* [/nl/docs/DOM/Storage](https://developer.mozilla.org/nl/docs/DOM/Storage) → [/nl/docs/Web/API/Web_Storage_API](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/API/Web_Storage_API)
* [/nl/docs/Web/CSS/CSS_Colors](https://developer.mozilla.org/nl/docs/Web/CSS/CSS_Colors) → [/nl/docs/Web/CSS/CSS_Color](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Web/CSS/CSS_Color)
* [/nl/docs/Web/CSS/Voor_Beginners](https://developer.mozilla.org/nl/docs/Web/CSS/Voor_Beginners) → [/nl/docs/Learn/CSS/First_steps](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/CSS/First_steps)
* [/nl/docs/Web/Guide/HTML/HTML5_audio_en_video_gebruiken](https://developer.mozilla.org/nl/docs/Web/Guide/HTML/HTML5_audio_en_video_gebruiken) → [/nl/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content](https://unslugged.content.dev.mdn.mozit.cloud/nl/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
