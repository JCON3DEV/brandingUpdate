# brandingUpdate


The following table provides a summary of the terms that are changing in accordance with the recent branding guidelines. When directly referenced in the documentation, all of the terms listed below should be updated to their rebranded counterparts as capabilities of Adobe Experience Platform. Each of these terms are no longer proper nouns, they are a non-specific reference to a capability and not a branded service, and as such they are to be written in lower case.

An example of this logic can be seen in the use of the word "schemas". For example, you would use an Experience Data Model (XDM) schema to describe the structure of data in a consistent and reusable way. As XDM is the specific name of a branded service, it is capitalized when written in full. The word schema however is a generic concept and as a common noun, is never capitalized.  

| Original Term  |Updated Term | Explanation  |Previous Example Sentence  | Current Branded Use |
|---|---|---|---|---|
| **Platform Launch** **(Client Side)** | tags | Simplistically speaking, "Platform Launch" is being replaced with the term tags. If context is required by removing "Launch" from the sentence, you can append "in Adobe Experience Platform" on the first instance to familiarize the reader. Subsequent references can simply refer to the suite of technologies as tags. | What is **Platform Launch?**  | What are **tags in Adobe Experience Platform?** |
|  **Platform Launch Server Side** |  event forwarding | "Launch Server Side" is now "event forwarding".   | See the **Launch Server Side** overview for more information.  | See the **event forwarding overview** for more information.  |
| **edge configuration**  |  datastream | The term "edge configuration" should be replaced with the lowercase noun "datastream". | Configure the Web SDK extension to send data to the **edge configuration** that you created previously.  | Configure the Web SDK tag extension to send data to the datastream created previously.  |

## Other branding considerations

### Tags is not a branded service

"Platform Launch" was widely regarded as a service like Analytics or Experience Cloud. Its conceptual separation into "Adobe Experience Platform" and "tags" as separate entities defines tags as a set of capabilities and not a branded service. This logic also extends to the treatment of "event forwarding" (formerly "Launch Server Side"). Event forwarding is also a capability provided under the grouping of Data Collection capabilities.

Aspects of the functionality previously attributed to the term "Launch" are now either encompassed by Platform (as a service) or determined by event forwarding and tags' capabilities. This can mean that instead of replacing the term Launch with tags, it is omitted from the sentence entirely.

An example where the reference to "Launch" can be omitted because Platform provides the functionality described in the sentence (and tags is a set of capabilities and not a service), can be seen here.

> **Platform Launch** passes `settings` into the rule’s condition-type library modules where conditions are then evaluated.

In the sentence above "Launch" is no longer necessary as the sentence was referring to the service provided. This is not part of Adobes new tag management system but a function of Platform. Instead it should instead be written as:

> **Platform** passes `settings` into the rule’s condition-type library modules where conditions are then evaluated.

### References to the Launch UI

The UI in Adobe Experience Platform that provides Platform Launch capabilities has now been renamed as the Data Collection UI. When a concept or capability is described as being "in" Launch, the author is likely referring to the Data Collection UI. An example of this can be seen below.

| Original Example | Updated sentence |
| --- | --- |
| **When configured in Adobe Experience Platform Launch**, this extension sends AEM Asset Impression and Click metrics to Adobe Analytics.| **When configured in the Data Collection UI**, this extension sends AEM Asset Impression and Click metrics to Adobe Analytics.|

Despite "Adobe Experience Platform Data Collection" appearing in the UI, you should avoid having "Adobe Experience Platform" and "data collection" next to each other since it is not a branded service. "Data Collection" is only capitalized in reference to the UI or when it is directly referred to as category of capabilities, although that is rare.

### Context and contractions

Another consideration when rebranding is the unnecessary or excessive reference to "Launch" or "Platform Launch" if context has already been established. In some cases, naming the capability in the sentence may be obsolete and can be removed entirely. The following sentence can be contracted as the context had already been established.

| Original Example | Updated sentence |
| --- | --- |
| If the extensions, tags, and systems you are going to deploy through **Platform Launch** are very similar across your sites or applications, you might want to include them in the same property. | If the extensions, tags, and systems you are going to deploy are very similar across your sites or applications, you might want to include them in the same property. |

### Referring to common nouns

Common nouns include concepts such as a runtime, libraries, data elements, and rules etc. The {tag/event forwarding} qualifier should be used before the common noun when the sentence requires context. If context is already established then the {tag/event forwarding} qualifier may be omitted. 

Use the singular version of "tag" when qualifying a general concept or process rather than the plural as "tags" refers to a suite of technologies. This is best demonstrated by referring to a tag rule or rules within tags as seen in the example sentences below.

> In the context of data collection tags, rules control the behavior of the resources in a deployed library.
<!-- help/api/endpoints/rules.md -->

and 

> The `/rules` endpoint in the Reactor API allows you to manage tag rules programmatically.

Below are other examples demonstrating the use of the singular version of "tag" when writing "tag {noun}" in a sentence.

| Original Example | Updated sentence |
| --- | --- |
| The Adobe Experience Platform **Launch runtime** is designed to support the following browsers:| **The tag runtime** in Adobe Experience Platform is compatible with multiple browsers: |
| When users install an extension to an Adobe Experience Platform **Launch property**, they will be shown the extension configuration view which your extension will provide.| When users install an extension to **a tag property**, they will be shown the extension configuration view which your extension will provide.|

### Referring to extensions (tag extensions or event-forwarding extensions)

Writing about extensions for both tags and event forwarding capabilities, follows the same format as dealing with common nouns. The name of the extension (proper noun) will precede the qualifier (either tag or event forwarding) followed by the word "extension" (common noun). 

The branding changes regarding event forwarding are handled in the same way as tags because they too are a suite of technologies and not a branded service. Another example is provided below. This format can be seen in the following examples. 

<!-- Get a better example for event forwarding tags seen below -->

| Original Example | Updated sentence |
| --- | --- |
| Learn about **the Adobe ContextHub extension in Adobe Experience Platform Launch**. | Learn about **the Adobe ContextHub tag extension in Adobe Experience Platform**. |
| Learn about **the Server Side Cloud Connector extension** in Adobe Experience Platform Launch.| Learn about **the Cloud Connector event forwarding extension** in Adobe Experience Platform. |

The context provided by "tag extension" or "event forwarding" negates the need for the wording "in Adobe Experience Platform", however it can be used to provide further contextual clarity on the first instance within the document.

### Example uses of original terms

The table below offers more guidance on the varying example uses of the original terms and how to apply the branding updates in a given situation. As any given term can be used in a variety of contexts, the table offers guidance on the nuance of the branding changes, including how they are applied and an explanation as to why.

| Example Use of Original Term  | Updated Wording | Explanation  |Previous Example Sentence  | Current Branded Use |
|---|---|---|---|---|
| **An Adobe Experience Platform Launch {noun}** | a tags-enabled {noun} | When tags is providing the functionality to the noun, the hyphenated "enabled" adds clarity to the sentence.  | This extension provides the functionality for adding the `Media` tracker instance to **an Adobe Experience Platform Launch site** or project.  | This extension provides the functionality for adding the `Media` tracker instance to **a tags-enabled site** or project.   |
| **Platform Launch {noun}**  |  a tags-enabled {noun} | When tags is providing the functionality to the noun, the hyphenated "enabled" adds clarity to the sentence.  | After you have included all three of the extensions mentioned above in your Platform Launch project, you can proceed in one of two ways:  | After you have included all three of the extensions mentioned above in your **tags-enabled project**, you can proceed in one of two ways:  |
| **Adobe Experience Platform Launch {verb} ...**  | Adobe Experience Platform {verb} | "Launch" is not always necessary and can be omitted. When the sentence refers to Launch as a service it can often be replaced by referring to Platform. | **Adobe Experience Platform Launch provides** a unified catalog where users can view tag extensions that are available for installation. | **Adobe Experience Platform provides** a unified catalog where users can view tag extensions that are available for installation. |

### edge and web extensions

Using the wording "an edge extension" or "a web extension" is fine for general use. However, if more context is required the sentence will need to be restructured using the "tag" or "event forwarding" qualifier before the edge specific common noun. An example below demonstrates this point.

| Original Example | Updated sentence |
| --- | --- |
| Learn how to define an action-type library module for an **edge extension in Adobe Experience Platform Launch.**| Learn how to define an action-type library module for **a tag extension in an edge property**. |



				