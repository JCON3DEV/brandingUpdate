# brandingUpdate

The table below provides a summary of the terms that are changing in accordance with the recent branding guidelines. When mentioned in the documentation, all of the terms listed below should be updated to their rebranded counterparts as generic capabilities of Adobe Experience Platform. These terms are not proper nouns, and therefore should not be capitalized. Instead, they should be written in lower case like other generic Platform capabilities like "schemas", "profiles", and so on. Rather than being capitalized, branded services, the new terms are styled as generic capabilities of Adobe Experience Platform.

| Original Term  |Updated Term | Explanation  |Previous Example Sentence  | Current Branded Use |
|---|---|---|---|---|
| **Platform Launch** **(Client Side)** | tags | Simplistically speaking, "Platform Launch" is being replaced with the term "tags". If more context is required by removing "Launch" from the sentence, you can append "in Adobe Experience Platform" on the first mention to familiarize the reader. Subsequent mentions can simply refer to the suite of technologies as tags. | What is **Platform Launch?**  | What are **tags in Adobe Experience Platform?** |
|  **Platform Launch Server Side** |  event forwarding | "Launch Server Side" is now "event forwarding".   | See the **Launch Server Side** overview for more information.  | See the **event forwarding overview** for more information.  |
| **edge configuration**  |  datastream | The term "edge configuration" should be replaced with "datastream". | Configure the Web SDK extension to send data to the **edge configuration** that you created previously.  | Configure the Web SDK tag extension to send data to the **datastream** created previously.  |

## Other branding considerations

The following sections contain additional guidance regarding the term changes described above.

### Tags is not a branded service

"Platform Launch" was widely regarded as a service like Analytics or Experience Cloud. Tags are a set of capabilities and not a branded service. The same applies to "event forwarding" (formerly "Launch Server Side"). Event forwarding is also a capability provided under the grouping of Data Collection capabilities.

In previous cases where "Platform Launch" is referenced as a service, the word "Launch" can simply be dropped, as Platform itself is now the service that provides tags, event forwarding, and datastreams. The following table provides some examples:

| Original example | Updated sentence |
| --- | --- |
|  **Platform Launch** passes `settings` into the rule’s condition-type library modules where conditions are then evaluated.  |  **Platform** passes `settings` into the rule’s condition-type library modules where conditions are then evaluated.  |
| **Adobe Experience Platform Launch provides** a unified catalog where users can view tag extensions that are available for installation. | **Adobe Experience Platform provides** a unified catalog where users can view tag extensions that are available for installation. |

### Mentions of the Launch UI

The "Platform Launch UI" has now been renamed as the "Data Collection UI". When a concept or capability is described as being "in Launch", the author is likely referring to the Data Collection UI. An example of this can be seen below.

| Original example | Updated sentence |
| --- | --- |
| **When configured in Adobe Experience Platform Launch**, this extension sends AEM Asset Impression and Click metrics to Adobe Analytics.| **When configured in the Data Collection UI**, this extension sends AEM Asset Impression and Click metrics to Adobe Analytics.|

Despite "Adobe Experience Platform Data Collection" appearing in the UI, you should avoid having "Adobe Experience Platform" and "data collection" next to each other since it is not a branded service. "Data Collection" is only capitalized when mentioned regarding the UI or a collection of technologies that include the Platform Web and Mobile SDKs, and Edge Network.

### Context and removing unneeded terms

Another consideration when rebranding is any unnecessary or excessive use of the terms "Launch" or "Platform Launch" if the context has already been established. In some cases, mentioning the capability in the sentence may be redundant and can be removed entirely. The following sentence can be contracted as the context had already been established.

| Original example | Updated sentence |
| --- | --- |
| If the extensions, tags, and systems you are going to deploy through **Platform Launch** are very similar across your sites or applications, you might want to include them in the same property. | If the extensions, tags, and systems you are going to deploy are very similar across your sites or applications, you might want to include them in the same property. |

### Referring to common nouns

Nouns that refer to tags- or event-fowarding-specific concepts such as a runtime, libraries, data elements, rules, etc., should be prepended with "tag" or "event-fowarding" when the sentence requires context. If context is already established then the qualifier is not needed. This is best demonstrated by the example sentences below.

| Original example | Updated sentence |
| --- | --- |
| The Adobe Experience Platform **Launch runtime** is designed to support the following browsers:| **The tag runtime** in Adobe Experience Platform is compatible with multiple browsers: |
| When users install an extension to an Adobe Experience Platform **Launch property**, they will be shown the extension configuration view which your extension will provide.| When users install an extension to **a tag property**, they will be shown the extension configuration view which your extension will provide.|

When tags are providing functionality to something else (like an app or a website), use the term "tags-enabled" to qualify these nouns. Below are some examples:

| Original example | Updated sentence |
| --- | --- |
| This extension provides the functionality for adding the `Media` tracker instance to **an Adobe Experience Platform Launch site** or project.  | This extension provides the functionality for adding the `Media` tracker instance to **a tags-enabled site** or project.   |
| After you have included all three of the extensions mentioned above in your **Platform Launch project**, you can proceed in one of two ways:  | After you have included all three of the extensions mentioned above in your **tags-enabled project**, you can proceed in one of two ways:  |

### Referring to extensions

Writing about extensions for both tags and event-forwarding capabilities follows the same format as dealing with common nouns. The name of the extension (a proper noun) precedes the qualifier (either "tag" or "event-forwarding") followed by the word "extension". For example: "the Adobe Privacy tag extension. This format can be seen in the following examples. 

| Original example | Updated sentence |
| --- | --- |
| Learn about **the Adobe ContextHub extension in Adobe Experience Platform Launch**. | Learn about **the Adobe ContextHub tag extension**. |
| Learn about **the Server Side Cloud Connector extension** in Adobe Experience Platform Launch.| Learn about **the Cloud Connector event-forwarding extension**. |

#### Edge and web extensions

Using the wording "an edge extension" or "a web extension" is fine for general use. However, if more context is required the sentence will need to be restructured using the "tag" or "event-forwarding" qualifier before the edge/web-specific common noun. An example below demonstrates this point.

| Original example | Updated sentence |
| --- | --- |
| Learn how to define an action-type library module for an **edge extension in Adobe Experience Platform Launch.**| Learn how to define an action-type library module for **a tag extension in an edge property**. |
				