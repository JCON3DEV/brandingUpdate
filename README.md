# brandingUpdate


The following table provides a summary of the terms that are changing in accordance with the recent branding guidelines. When directly referenced in the documentation, all of the terms listed below should be updated to their rebranded counterparts as capabilities of Adobe Experience Platform. Each of these terms are no longer proper nouns, they are a non-specific reference to a capability and not a branded service, and as such they are to be written in lower case.

An example of this logic can be seen in the use of the word "schemas". For example, you would use an Experience Data Model (XDM) schema to describe the structure of data in a consistent and reusable way. As XDM is the specific name of a branded service, it is capitalized when written in full. The word schema however is a generic concept and as a common noun, is never capitalized.  

| Original Term  |Updated Term | Explanation  |Previous Example Sentence  | Current Branded Use |
|---|---|---|---|---|
| **Platform Launch** **(Client Side)** | tags | If context is required by removing "Launch" from the sentence, you can append "in Adobe Experience Platform" on the first instance. Subsequent references can simply refer to the suite of technologies as tags. | What is **Platform Launch?**  | What are **tags in Adobe Experience Platform?** |
|  **Platform Launch Server Side** |  event forwarding | "Launch Server Side" is now "event forwarding".   | See the **Launch Server Side** overview for more information.  | See the **event forwarding overview** for more information.  |
| **edge configuration**  |  datastream | The term "edge configuration" should be replaced with the lowercase noun "datastream". | Configure the Web SDK extension to send data to the **edge configuration** that you created previously.  | Configure the Web SDK tag extension to send data to the datastream created previously.  |

The UI in Adobe Experience Platform that provides Platform Launch capabilities has now been renamed as the Data Collection UI. When a concept or capability is described as being "in" Launch, the author is likely referring to the Data Collection UI. An example of this can be seen below.

> **When configured in Adobe Experience Platform Launch**, this extension sends AEM Asset Impression and Click metrics to Adobe Analytics.

The sentence above can therefore be rewritten as:

> **When configured in the Data Collection UI**, this extension sends AEM Asset Impression and Click metrics to Adobe Analytics.

Despite "Adobe Experience Platform Data Collection" appearing in the UI, you should avoid having "Adobe Experience Platform" and "data collection" next to each other since it is not a branded service. "Data Collection" is only capitalized in reference to the UI or when it is directly referred to as category of capabilities, although that is rare.

Another consideration when rebranding is the unnecessary or excessive reference to "Launch" or "Platform Launch" if context has already been established. In some cases, naming the capability in the sentence may be obsolete and can be removed entirely. An example of this can be seen below.

> If the extensions, tags, and systems you are going to deploy through **Platform Launch** are very similar across your sites or applications, you might want to include them in the same property.

This sentence can be contracted as the context had already been established.

> If the extensions, tags, and systems you are going to deploy are very similar across your sites or applications, you might want to include them in the same property. |

<!-- Break this down. Go into detail of how to tell if you're talking about Launch as a service (now Platform), versus Launch as a set of capabilities (tags or event forwarding) -->

| **Platform Launch**  | Platform  | The reference to Launch is not always necessary if the sentence was referring to the service provided. In this case "Launch" can be omitted because tags is a set of capabilities and not a service. Here, Platform provides the functionality.  | **Platform Launch** passes `settings` into the rule’s condition-type library modules where conditions are then evaluated. | **Platform** passes `settings` into the rule’s condition-type library modules where conditions are then evaluated. |

<!--  -->

The table below offers more comprehensive guidance on the varying example uses of the original terms and how to apply the branding updates in a given situation. As any given term can be used in a variety of contexts, the table offers guidance on the nuance of the branding changes, including how they are applied and an explanation as to why.

| Example Use of Original Term  | Updated Wording | Explanation  |Previous Example Sentence  | Current Branded Use |
|---|---|---|---|---|
| **An Adobe Experience Platform Launch {noun}** | a tags-enabled {noun} | When tags is providing the functionality to the noun, the hyphenated "enabled" adds clarity to the sentence.  | This extension provides the functionality for adding the `Media` tracker instance to **an Adobe Experience Platform Launch site** or project.  | This extension provides the functionality for adding the `Media` tracker instance to **a tags-enabled site** or project.   |
| **The Launch runtime**  |  The tag runtime | Use the singular version of "tag" and "The" as an article when talking about a general concept/process rather than individual runtime events.  | **The Adobe Experience Platform Launch runtime** (delivered to clients' websites) is designed to support the following browsers:  | **The tag runtime** in Adobe Experience Platform (delivered to clients' websites) is compatible with multiple browsers:  |
| **A Launch property**  | A tag property  | Use the singular version of "tag" when writing "tag {noun}" in a sentence. | When users install an extension to an Adobe Experience Platform **Launch property**, they will be shown the extension configuration view which your extension will provide.  | When users install an extension to **a tag property**, they will be shown the extension configuration view which your extension will provide.  |
| **the {noun} extension in Platform Launch**  |  the {noun} tag extension in Platform | The name of the extension will precede the tag qualifier. Later references to tags (Launch) are removed once context has been established.  | Learn about **the Adobe ContextHub extension in Adobe Experience Platform Launch**. | Learn about **the Adobe ContextHub tag extension in Adobe Experience Platform**.  |
| **Adobe Experience Platform Launch {verb} ...**  | Adobe Experience Platform {verb} | "Launch" is not always necessary and can be omitted. When the sentence refers to Launch as a service it can often be replaced by referring to Platform. | **Adobe Experience Platform Launch provides** a unified catalog where users can view tag extensions that are available for installation. | **Adobe Experience Platform provides** a unified catalog where users can view tag extensions that are available for installation. |
| **An edge extension in Launch** | an edge extension OR a tag extension in an edge property  | An edge extension is not to be confused with an edge configuration. Using "an edge extension" is fine for general use. This example only applies if more context is required.  | Learn how to define an action-type library module for an **edge extension in Adobe Experience Platform Launch.** | Learn how to define an action-type library module for **a tag extension in an edge property**.  |

The following table provides an example of event forwarding branding guidelines. It is handled in the same way as tags in that it is a suite of technologies and not a Branded service. It is referred to in lower case.

| Original Term  |Updated Term | Explanation  |Previous Example Sentence  | Current Branded Use |
|---|---|---|---|---|
| **the Server Side Cloud Connector extension**  | the Cloud Connector event forwarding  extension	| The name of the extension will precede the "event forwarding extension" qualifier. Also, as context is established by the term "event forwarding", "Launch" can be removed from adjoining sentences.  | Learn about **the Server Side Cloud Connector extension** in Adobe Experience Platform Launch.  |  Learn about **the Cloud Connector event forwarding extension** in Adobe Experience Platform. |

<!-- below is simply another example of when to use a tags-enabled {noun} it can probably be deleted. -->
<!-- | **Platform Launch {noun}**  |  a tags-enabled {noun} | When tags is providing the functionality to the noun, the hyphenated "enabled" adds clarity to the sentence.  | After you have included all three of the extensions mentioned above in your Platform Launch project, you can proceed in one of two ways:  | After you have included all three of the extensions mentioned above in your **tags-enabled project**, you can proceed in one of two ways:  | -->
				