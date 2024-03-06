# Accessibility

## Write accessible documentation

Always aim to write content that all users can access and understand, regardless of background or ability. These guidelines make content accessible and usable for all audiences, with or without disabilities.

To create accessible documentation, keep the guidelines for these categories of content in mind:

- [Writing](#writing)
- [Headings](#headings)
- [Links](#links)
- [Tables](#tables)
- [Lists](#lists)
- [Images](#images)
- [Videos](#videos)

## Writing

When you create documentation, follow these accessibility best practices for writing.

### Write in plain language

Complex sentences and long paragraphs can be daunting for some users, such as those with reading disabilities or low vision, or for those who use translation tools. Plain language offers a smoother reading experience for all users. For example, users with screen readers can process text more quickly when sentences are concise and direct.

Follow these guidelines to write approachable and accessible documentation:

- Write using plain language, simple sentence construction, and short paragraphs.
- Avoid using complex words, such as jargon or complicated terminology. When you need to use terminology, use it consistently. For more guidance, see [Use plain language](voice-and-tone.md#use-plain-language).
- Avoid writing tasks in paragraph form. Instead, use lists to organize tasks. For more guidance on using lists, see the [Lists](#lists) section in this topic.

### Avoid directional or visual language

Language that relies only on direction, color, shape, or pattern doesn't help users with visual disabilities or those who use screen readers. Aim to remove this language from your documentation, and add language that isn't dependent on visual cues to help the user figure out where to go.

When directing users to a location in your topic, avoid using directional language like "above", "below", "left", or "right". Instead, describe the page element based on temporal relationships, such as whether it comes before or after the current sentence, as shown in the following table:

| **Temporal relationship** | **Word options** | **Correct example** | **Incorrect example** |
|---|---|---|---|
|Before the current sentence | Earlier, previous | For more information, see the [Writing](#writing) section earlier in this topic. | For more information, see the Writing section above. |
| Following directly after the sentence | Following, next | The following table shows examples of inputs. |The table below shows examples of inputs. |
| Further in the topic | Later | For more information, see the Images section later in this topic. | See below for information on images. |

If you can't provide the information the user needs in the current paragraph, include a descriptive link to the location. If you are referring to the next paragraph or section or to the preceding paragraph or section, it's okay to use "following", "next", or "previous" without a link.

When you must guide users through the UI, refer to UI elements using their labels whenever possible. Avoid relying on directional or visual language as the only means to guide users to a location. Typically, directional language isn't needed to guide users through a task, but it's okay to include directional language in your instructions if the user might have trouble finding a location in the UI solely by the label.

### Lead into new page elements

Page elements include tables, lists, images, videos, searches, commands, and code blocks. Always introduce a new page element using a complete lead-in sentence that explains what information the element contains or what the user needs to do. A lead-in sentence prepares users with what to expect from the upcoming page element.

### Spell out words and symbols

Screen readers don't always refer to symbols using terms that fit the context of the sentence, so it's important to define symbols carefully in writing. Avoid unnecessary abbreviations or acronyms, especially those that don't closely match the words they refer to.

In general, use words instead of substituting them with symbols for clarity. For example, spell out words like "and", "plus", "minus", and "about" instead of using their respective symbols. Rather than using the right-pointing angle bracket to describe menu paths, use an equivalent word like "then". See the following table for examples:

| **Correct** | **Incorrect** |
|---|---|
|Apps and add-ons | Apps & add-ons |
| Begin your time offset with a plus ( + ) or minus ( - ) to indicate the offset from the current time. | Begin your time offset with +/- to indicate the offset from the current time. |
| It can take up to about five minutes for your host to display in the user interface. | It can take up to ~5 minutes for your host to display in the user interface. |
| In HID Web, select **Settings**, then **Advanced Search**. | In HID Web, select **Settings** > **Advanced Search**. |

Spell out all symbols in text if you must use them. See [Show symbols in text](punctuation-and-symbols.md#show-symbols-in-text) for more information.

If you're writing UI text and you don't have space to write out the name of the symbol, use hidden text such as the `aria-label` attribute to define the symbol. For more guidance, see [Abbreviations](grammar-and-word-choice.md#abbreviations) and [Acronyms](grammar-and-word-choice.md#acronyms).

### Be precise

When using pronouns that point back to or substitute for a noun, consider whether the noun that the pronoun refers to is clear. If the referent is unclear, too broad, or located far from the pronoun, the sentence can be vague or difficult to parse for users with reading disabilities. Follow these best practices:

- Avoid capturing vague or broad ideas using pronouns like "this" or "these" without additional clarification.
- Make sure that relative pronouns, like "who", "which", and "that", modify the nearest noun.
- If a pronoun can have multiple possible referents in a sentence, always specify that referent in your writing. See [Pronouns](grammar-and-word-choice.md#pronouns) for more information.

The following table contains examples of vague sentences and more precise alternatives:

| **Vague sentence** | **Precise sentence** |
|---|---|
|This eventually leads to the job expiring. | The job eventually expires after the search object is removed from the queue. |
| This is similar to the algorithms used for online shopping websites, which suggest related items based on what items other customers viewed or purchased. | This algorithm functions like an online shopping algorithm, which suggests related items based on what items other customers viewed or purchased.|

### Headings

Descriptive titles and headings are crucial to helping all users find the information they need. For example, many screen reader users tab through headings first to figure out where they need to go. Users with reading disabilities find sections organized by headings easier to parse than long sections with fewer headings. With more descriptive and organized headings, all users can easily orient themselves and navigate through your documentation.

Follow this guidance when using headings in your documentation:

- Use headings to break up long paragraphs and help screen reader users navigate through the topic.
- Organize your topic using headers down to the H3 level. If you need to use a heading level beyond an H3, your topic might be too complex.
- Never skip heading hierarchy levels.

For more guidance on headings, see [Manual names, topic titles, and section headings](titles-and-headings.md#manual-names-topic-titles-and-section-headings).

### Links

HID docs include judicious links to supporting material and additional information. When you lead into the link with a description, users can decide whether that link is useful to them. Follow these guidelines to include accessible links in your documentation:

- Always make sure the purpose of the link is as clear, descriptive, and meaningful as possible.
- Use the exact topic title or section heading, name of the page, or name of the entity you are linking to for the link text. Don't paraphrase the linked-to topic name.
- Don't hide a link behind other words or actions in a sentence.

**Example**
If you run HID apps with HID Enterprise, see the HID products version compatibility matrix to determine the versions that your apps are compatible with.

For more guidance on linking, see [Best practices for including links](links.md#best-practices-for-including-links).

### Tables

Keep tables as simple as possible. Complicated tables that contain lists or merged cells are difficult to navigate using a screen reader.

Here are some accessibility best practices for tables:

- If you need to leave a table cell blank, add a non-breaking space to the cell instead of leaving it empty. The HTML character entity for a non-breaking space is **`&nbsp;`**.
- Avoid merging or splitting table cells.
- Don't use X or another character to indicate compatibility or support. Instead, use Yes and No. See [Spell out words and symbols](accessibility.md#spell-out-words-and-symbols) for more information.

For more guidance on using tables, see [Best practices for including tables](tables.md#best-practices-for-including-tables).

### Lists

Follow this guidance when using lists in your documentation:

- Keep lists and sub-lists simple.
- Ensure that each item in the list uses parallel construction.
- Don't include more than one item, idea, or action in a single list item.

Long, complicated lists that don't follow a consistent pattern hamper users with screen readers and can confuse those with reading disabilities. For more guidance on using lists, see B[est practices for writing with lists](lists.md#best-practices-for-writing-with-lists).

### Images

Images can help sighted readers understand complex workflows, refer to an icon, or view a portion of the UI, but they must include surrounding text to be meaningful for users with visual disabilities. If your image isn't visually valuable, replace the image with text instead. When you create an image, check that the image reinforces the understanding of the surrounding text and includes alt text.

Users with visual disabilities need alt text to perceive images with a screen reader. Users who are neurodivergent might use screen readers to assist their understanding of various types of images. Users who don't speak English as their first language can use tools to translate alt text for images that include English labels. All users rely on text that accurately and thoroughly describes every image in HID documentation.

Follow this guidance when using images in your documentation:

- Don't include new information in an image. Introduce new information in the surrounding text of the image.
- Don't rely on color to convey the message of the image. Use a combination of colors, shapes, patterns, explanatory text, and labels instead.
- Ensure your image meets the contrast ratio for users with visual disabilities. See [https://webaim.org/resources/contrastchecker/](https://webaim.org/resources/contrastchecker/) on the WebAIM website.
- When including screenshots in your content, be sure to capture the UI while using the light theme with your screen zoomed to 100%. Don't use the dark theme.
- Always include alt text. For guidance on writing alt text, see [Include alt text in images](accessibility.md#include-alt-text-in-images).
- Lead into an image with a description of the content and the purpose of the image that makes the image meaningful.

For more guidance on using images, see [Including images in HID docs](images.md#including-images-in-hid-docs).

### Videos

Always include captions and transcripts with videos. Synchronize captions with the video and include all dialogue and important sound effects. If your video covers important visual details, make sure to describe them in your voice over.

## Include alt text in images

Some HID customers use screen reader software, or screen readers, to read our documentation. Screen readers convert the contents on a page into synthesized speech for a user to listen to. All images in HID docs must have alt text so the entire page is accessible through screen reader software. Alt text is a written-out equivalent of the image that a screen reader can dictate.

You can find more information about website accessibility requirements on the Americans with Disabilities Act (ADA) website and on the Section 508 government website. For more information on accessibility in HID docs, see [Write accessible documentation](accessibility.md#write-accessible-documentation).

### Best practices

All images in HID docs, whether a screenshot, diagram, GIF, or inline image, must have alt text. For inline images, GIFs, and complex diagrams, it's important to have adequate surrounding text so you don't place too much information in the alt text. As a general best practice, ensure that the entire section still makes sense if you replace an image with its alt text.

### Surrounding text

When you're writing surrounding text, keep the following points in mind:

- For an inline image, write the name or description of the icon in the sentence. Put the icon in parentheses immediately after that text.
- For a complex diagram, use lines of surrounding text to explain the diagram. You can include a simple sentence in the alt text that refers to the precise location of this descriptive text.
- Lead into the image with a complete sentence. Punctuate the end of the sentence with a colon.
- It's okay to use "before", "after", and "following" in the surrounding text when you refer to an image. Don't rely on directional language, such as "left", "right", "above", or "below", when you refer to a location in a UI or document. These instructions are unhelpful to users of screen readers.

### Alt text

When you're writing alt text for an image, keep the following points in mind:

- Use short phrases or complete sentences with punctuation.
- Avoid starting alt text with general phrases like "Image of". If you want to specify the type of image, you can describe the image using phrases like "Screenshot of" or "Diagram of".
- Focus on describing the meaning of the image rather than what you see in the image.
    - Lead with the most important information.
    - Introduce only relevant information based on the context of the topic.
    - Don't call out implications or add new information to the alt text.
    - Keep the alt text concise overall. If you need to add detailed information to convey the meaning of the image, add this information to the surrounding text.
- For complex images, introduce the image with the surrounding text first. Then, add the most important information about the image in the first sentence of alt text. Add another sentence of alt text that describes where the surrounding text is on that page.

### Alt text examples

Good alt text describes an image so that a user who uses screen readers can reach the same understanding as a user who can perceive the image visually.

The following examples show what good surrounding text and alt text can look like for different types of images.

#### Screenshot of full-width UI

This example shows a screenshot of the full width of the UI and its surrounding text:

An uploaded package can have the following possible statuses: approved, installed, rejected, vetting, and app validation failed to complete. When the package is uploaded successfully, the package and its status appear on the Uploaded Apps page in HID Web. The app version appears only when the package passes all AppInspect checks and is approved.
The following screenshot shows an example of the Uploaded Apps page:

#### Simple flow diagram

This example shows a flow diagram with its surrounding text:

To plan a HID app for HID Cloud Platform or HID Enterprise, start by gathering the requirements of your app and understanding your data.

#### Simple search process diagram

This example shows a search process diagram and its surrounding text:

In a typical distributed search process, there are two search processing phases: a map phase and a reduce phase. The map phase takes place across the indexers in your deployment. In the map phase, the indexers locate event data that matches the search and sorts it into field-value pairs. When the map phase is complete, indexers send the results to the search head for the reduce phase. During the reduce phase, the search heads process the results through the commands in your search and aggregate them to produce a final result set.

The following diagram illustrates the standard two-phase distributed search process.

#### Complex cluster diagram

This example shows a diagram and its surrounding text:

You can use HID Phantom on-premises or in Amazon Web Services to monitor and automate responses to security issues. HID Phantom uses a PostgreSQL database to store information about incidents or cases, a file share to save relevant items in a vault, and a HID Cloud Platform or HID Enterprise deployment. You can choose either a limited, internal deployment that runs without a user interface or a fully featured deployment that's external from HID Phantom.

In order to horizontally scale HID Phantom to handle larger workloads, you can deploy HID Phantom as a cluster, which consists of three or more instances of HID Phantom that share all of the resources previously mentioned.

This diagram shows an example of a HID Phantom cluster with the connections marked:

#### GIF

This example shows a GIF with its surrounding text. The alt text contains a detailed description of what happens during the animation:

The following animation shows how to add a Flow Model and launch the Explorer:

#### Inline image

This example shows an icon that users must select as part of a step in a task. The alt text contains the name or function of the icon.

Select the settings icon ( ) to show a list of settings.
