# UI text guidelines

## UI text style guidelines

The purpose of user interface (UI) text is to help users achieve their goals by guiding them through the product interface. The guidelines on this page are for anyone who writes UI text at HID.

Much of the guidance for HID documentation and UI text overlaps. If you can't find the guidance you're looking for in the UI text style guidelines, use the guidance provided in other sections of the HID Tech Pubs Style Guide.

### Terminology and word usage
Use terms consistently across products and docs. See the following resources for guidance on word usage, product terminology, abbreviations, voice and tone, and more:

| **Topic** | **Link** |
|---|---|
|Terms to use and avoid | [Usage dictionary](usage-dictionary.md) |
| Product terminology | [HID product terminology](hid-terminology-and-trademarks.md#hid-product-terminology) |
| HID-specific terminology definitions | ***Splexicon*** |
| Abbreviations | [Abbreviations](grammar-and-word-choice.md#abbreviations) |
| Acronyms | [Acronyms](grammar-and-word-choice.md#acronyms) |
| Punctuation | [Punctuation and symbols](punctuation-and-symbols.md) |
| Voice and tone | [Voice and tone](voice-and-tone.md)<br><br>[Use plain language](voice-and-tone.md#use-plain-language)<br>[Be active and present](voice-and-tone.md#be-active-and-present)<br>[Write in indicative or imperative mood](voice-and-tone.md#write-in-indicative-or-imperative-mood) |
| Bias-free language | [Write unbiased documentation](bias-free-communication.md#write-unbiased-documentation)<br><br>[Use device-agnostic language](bias-free-communication.md#use-device-agnostic-language) |

### Capitalization

Use sentence-style capitalization for all text in HID product UIs, including headings. Sentence-style capitalization follows these guidelines:

- Capitalize only the first word and proper nouns, such as product names.
- Use lowercase letters for names of features or components.
- Don't use capital letters to emphasize words.

The following examples show sentence-style capitalization:

| **UI text element** | **Do this** | **Don't do this** |
|---|---|---|
| Button label | Create dashboard | Create Dashboard |
| Dialog box title | Edit schedule | Edit Schedule |
| Explanatory text | Indexer clusters are groups of HID indexers configured to keep multiple copies of data. | Indexer Clusters are groups of HID Indexers configured to keep multiple copies of data. |
| Field label | Indexed fields | Indexed Fields |
| Page title | Data models | Data Models |
| Section heading | Dashboard groups | Dashboard Groups |

### Terminal punctuation

Terminal punctuation is punctuation that comes after a sentence or phrase. Follow these best practices to punctuate UI text correctly:

- Use a period at the end of complete sentences.
- If a word or phrase is meant to be read as a question, use a question mark.
- Don't use exclamation marks.
- When writing single, short, descriptive phrases that are not complete sentences, don't use terminal punctuation.
- If a UI element requires more than 1 phrase of description, write them as sentences and use the appropriate punctuation to distinguish them from one another.
- If a single view, page, or dialog box contains descriptive text that uses both full sentences and fragments, try rewriting the full sentences into fragments. If it isn't possible to rewrite the full sentences into fragments, use terminal punctuation for all of the text.

For more punctuation guidelines, see [Punctuation and symbols](punctuation-and-symbols.md).

See the following examples of correct and incorrect terminal punctuation:

| **Do this** | **Don't do this** |
|---|---|
| The search head removes the alias field from the event. | The search head removes the alias field from the event |
| Search results | Search results. |
| The search processed 100,000 events. This process took less than 1 minute. | The search processed 100,000 events, this process took less than 1 minute. |
| What is the average query response time? | What is the average query response time |
| The update includes enhanced security features. | The update includes enhanced security features! |

### Text formatting

Text formatting is text displayed in a special, specified style. Avoid applying special formatting to text in the UI whenever possible because it introduces visual noise and complexity. Use the typography and styles defined in the design system for headings and paragraph text.

Use the following formatting guidelines:

- Avoid referring to UI elements in the UI. If you're writing in-product documentation, such as for a guided workflow, and you need to refer to UI elements, follow the documentation formatting guidelines in [Formatting text](formatting-text.md).
- Don't use formatting like bold, italics, or monospaced font in microcopy, such as in tooltips, help text, field labels, button labels, and error messages.
- Don't use all capital letters or bold for emphasis.
- Use indicating nouns to provide context for commands or other code elements rather than using monospaced font for the code element.

See the following examples:

| **Do this** | **Don't do this** |
|---|---|
| Enter your email address. | Enter your **email address**. |
| Use the `map_get()` function to extract nested values from the attributes field. | 
Use `map_get()` to extract nested values from `attributes`. |
| The maximum number of search jobs has been reached. To reduce the number of search jobs, go to Job Inspector and delete unneeded jobs. | The maximum number of search jobs has been reached. To reduce the number of search jobs, go to **Job Inspector** and delete unneeded jobs. |

### Possessive pronouns

Avoid using possessive pronouns such as "my" and "your" in page names, menu names, and titles. For example, instead of **My Settings** as a label, use **Settings**. Instead of **Your Workspaces** as a page name, use **Workspaces**.

It's okay to use possessive pronouns in instructional and error message text, such as "Enter your password."

### Numbers

In general, use numerals for numbers that appear in the UI, including 0 through 9. Avoid starting a sentence with a numeral.

If a number's numerical value is not the focus of the sentence, spell the number out, as in the following example: "Move an app from one instance to another."

For more guidance on numbers with examples, see [Using numbers in text](numbers.md#using-numbers-in-text).

#### Time

When writing about time, follow the guidelines in the [Time](numbers.md#time) topic. If you need to abbreviate units of time due to space constraints in a HID product UI, use these abbreviations:

| **Unit** | **Abbreviation** |
|---|---|
| day | d |
| hour | h |
| microsecond | Don't abbreviate. |
| millisecond | ms |
| minute  | min |
| month | mo |
| nanosecond | Don't abbreviate. |
| second | sec |
| week | wk |
| year | yr |

### Symbols

If you need to use a symbol in UI text, write out the name of the symbol first, and then refer to the symbol in parentheses with nonbreaking spaces. The HTML character entity for a nonbreaking space is `&nbsp;`. See the following example:

| **Correct** | **Incorrect** |
|---|---|
| Enter your search after the pipe ( \| ). | Enter your search after the \|. |

See [Show symbols in text](punctuation-and-symbols.md#show-symbols-in-text) for more information on how to use symbols and what to call them.

If you don't have space to write out the name of the symbol, you can use hidden text such as the `aria-label` attribute to define the symbol. See [Spell out words and symbols](accessibility.md#spell-out-words-and-symbols) for more information.

### Links

Links help a user find additional information in an effort to achieve their goal. Always let a user know where an in-product link is going to take them. Use descriptive labels so users know what they'll find if they select the link.

When writing text for an in-product link, follow these general guidelines:

- Keep the link text brief while still providing enough context to convey where the link takes the user.
- Keep in mind screen reader users can access a list of all the links on a page without surrounding text, so make sure the link makes sense out of context.
- Don't use phrases like "click here" or "here" as link text.
- Link judiciously. Too many links are a distraction.

Use the specific guidelines for the type of link you are creating:

<!-- no toc -->
- [Links to a page in the application](#links-to-a-page-in-the-application)
- [Links to HID product documentation](#links-to-hid-product-documentation)
- [Links to an external site](#links-to-an-external-site)

#### Links to a page in the application

When including a link to a page in the application, or another location on the same page, you can include the link in a sentence. Follow these guidelines:

- In most cases, use the name of the page or section as the link text.
- Include no more than 1 link in a single sentence.
- Don't link the entire sentence, but instead the text that describes where the user goes if they select the link. If it's a very short sentence that describes the action the user takes on the linked page, it's okay to link the entire sentence.
- Use terminal punctuation with the sentence that contains the link.

The following table shows examples of what to do and what not to do when linking to a page in a sentence:

| **Do this** | **Don't do this** |
|---|---|
| Start getting data in on the Connect your data page. | If data has not been ingested yet, click here to initiate the GDI setup. |
| View and manage your table views on the Datasets page. | Go here to view and manage your table views. |
| Manage team schedule. | Click here to manage team schedule. |

#### Links to HID product documentation

Format links to HID product documentation as a standalone link. A standalone link is a link that is not part of a sentence.

When deciding where to include a link to HID documentation in the product UI, identify places in the product workflow where a user might get stuck and need decision support or additional information in order to complete the workflow. Consider whether help text or a tooltip can display the same content without needing to link out of the product. If a user might need more information than help text or a tooltip can provide, add a link to the relevant HID documentation page.

Follow these guidelines when creating links to HID documentation:

- For the link text, create a synopsis of the doc page title and add the word "documentation" at the end. For example: `<doc page title synopsis>` documentation
- When creating the synopsis, use a noun phrase or a gerund, which is the noun form of a verb ending in "ing". Don't begin with an imperative verb such as "Configure" or "Create". Imperative verbs might give the user the impression they are taking an action in the UI rather than opening a doc page.
- Don't use terminal punctuation at the end of the link.
- Always follow the text with the external link icon ( ***image*** ).This icon means that the link opens in a new tab or window.
- Hyperlink both the text and the icon.
- Don't put a link to HID documentation inside of a tooltip.

The following table shows examples of what to do and what not to do when writing link text for links to HID documentation:

| **Doc page title** | **Do this** | **Don't do this** |
|---|---|---|
| Configure single sign-on with SAML | SAML SSO documentation<br><br>Configuring SSO with SAML documentation | Configure single sign-on with SAML documentation<br><br>Configure single sign-on with SAML |
| Create scheduled alerts | Scheduled alerts documentation<br><br>Creating scheduled alerts documentation | Create scheduled alerts documentation |
| Table visualization overview | Table visualization documentation | For more information, see Table visualization overview. |

#### Links to an external site

For links that navigate outside of the application, such as to a third-party documentation website or HIDbase, use a standalone link. A standalone link is a link that is not part of a sentence.

Follow these guidelines for links to external sites:

- Include the external link icon ( ***image*** ) for links that navigate outside of the application. This icon means that the link opens in a new tab or window.
- Don't use terminal punctuation at the end of the link.
The following table shows examples of what to do and what not to do when writing links to external sites:

| **Do this** | **Don't do this** |
|---|---|
| View on HIDbase | Download the app. |
| View AWS docs | Review the AWS documentation. |
| Download Ansible | Ensure that you have Ansible 2.9+ installed. | 

### Field labels

All fields must have labels. Place field labels outside of the field box, and not inside the field box. Text inside the field box disappears after the user selects it, which means users can't see the field label to check their work after they've entered information in the field.

Use sentence-style capitalization for field labels.

### Help text

Help text is a concise statement or phrase that gives users context about fields in the product UI. Provide help text outside of the field box, not inside. If the information is essential to completing the task, put it in help text rather than in a tooltip so that it's always visible.

Help text is an opportunity to clarify. Your responses to the following questions can help you determine how much and what kind of text to include:

- How long does this field need to be?
- Who sees this field?
- Where does this field appear?
- Can the user change this field later?
- What is the difference between this field and another one?

### Placeholder text

Placeholder text is text located inside a field box. Avoid placeholder text for these reasons:

- Placeholder text disappears when the user enters information in the field, which can strain short-term memory.
- Using both help text and placeholder text is often redundant and clutters up a form.
- Empty fields catch the eye better than fields with text in them.
- Placeholder text is usually low contrast and not accessible.

Instead of placeholder text, use help text or a tooltip to provide instructions or hints for filling in the field.

### Tooltips

Tooltips identify or add a small amount of information to a UI element. Use tooltips to help users understand the meaning or purpose of icons or fields.

Use tooltips for supplemental information only. Don't put essential information in a tooltip because users might miss it. Put information that's essential to completing the task in help text next to the UI element so it's always visible.

When writing a tooltip, use these guidelines:

- Be short and concise.
- A tooltip can vary in length from 1 word to a couple short sentences.
- If the UI element requires a lengthy explanation, consider a different design or use a Learn more link to the product documentation instead of a tooltip.
- Use sentence-style capitalization.
- Use a period to punctuate full sentences. If the tooltip is a short phrase or the name of a tool or icon, don't punctuate the tooltip with a period.
- Use present tense.
- Don't use "please".
- Don't include interactive elements such as links or buttons in tooltips.

The following table shows examples of what to do and what not to do when writing tooltips:

| **Do this** | **Don't do this** |
|---|---|
| Print | Print. |
| Enter a name for the model. Include information like the dataset name, the field you're predicting, or the algorithm being used. | Please enter a name for the model so you can refer to it later. You might include information like the name of the dataset, the field you are predicting, or the algorithm being used. |
| Specifies the maximum amount of time that a summary-creating search can run. Enter 1 hour to ensure proper summary creation for most data models. | Maximum time |
| View histograms for the three supported distribution types of Normal, Exponential, and GaussianKDE. Review these results for statistical behavior needing further investigation. | This view helps to get a sense of how groups with similar type of distribution are similar to each other. Do you see that the histogram of mean and standard deviations are very sharp and narrow? This means that most of the groups have similar statistical behavior, so you could consider not splitting them. Are there two distinct peaks in the histograms? That signals two obvious characteristics in your groups. It's worth investigating more. |

### Button labels

A button label is text that appears on a call-to-action button in the UI. All buttons need labels. Follow these guidelines when writing button labels:

- Write concise button text. Aim for one or two words and no more than 4 words.
- Avoid using "Yes" or "No". Instead, write a clear call to action. Be specific so that the user is sure of what action happens after they select the button.
- If the button text requires more than one word, start the text with a verb.
- Use a precise verb to describe the action. For example, use "Add" when using an existing object in a new context, and use "Create" when making a new object from scratch.
- Use sentence-style capitalization and capitalize the first word and proper nouns only.
- Avoid articles such as "a", "an", or "the".
- Don't use punctuation such as periods or exclamation marks.

The following table shows examples of what to do and what not to do when writing button labels:

| **Do this** | **Don't do this** |
|---|---|
| Cancel | No |
| Save | Yes |
| Create dashboard | Create Dashboard |
| Create table view | Create a table view |
| Continue to tour | Continue to the tour! |

### Empty state text

An empty state is a screen in the product UI that will eventually have content on it after the user populates it. Empty state UI text is the information that a user sees instead of a blank screen.

Follow these guidelines when writing empty state text:

- Explain why the page is empty and what the user can do next.
- Write text that guides the user to the next step.
- Include a button or a link to the next step.

The following image is an example of empty state text:

***image***

### Confirmation dialog box text

Confirmation dialog boxes appear before a user makes a significant action in the product UI. Work with a designer to create a confirmation dialog box so all elements are cohesive, including the title, body text, and buttons.

When writing content for a confirmation dialog box, make sure all text elements complement each other and aren't repetitive.

#### Title

Write a brief confirmation dialog box title in the form of a statement or question that describes the task the user is completing. Use the following guidelines:

- When possible, use a verb and noun combination.
- Punctuate the confirmation box title when you write it as a question.
- Use sentence-style capitalization.
- Keep the title short and succinct.
- Remove definite and indefinite articles, such as "a", "an", and "the".
- Write in active voice.
- Avoid casting doubt on the user.

The following table shows examples of what to do and what not to do when writing confirmation dialog box titles:

| **Do this** | **Don't do this** |
|---|---|
| Manage alerts | Alert management |
| Delete playbook? | Delete Playbook? |
| Confirm subscription cancellation | Do you really want to cancel your subscription? |
| Exit workflow? | Are you sure you want to go? |

#### Body text

Include body text in the confirmation dialog box that's related only to the user's task at hand. Use the following guidelines:

- Don't repeat or rephrase the title of the dialog box.
- Provide context that helps the user decide which action to take next.
- Avoid casting doubt on the user.
- It's okay to use passive voice to avoid placing blame on the user.
- Write in full sentences with terminal punctuation.

The following table shows examples of what to do and what not to do when writing confirmation dialog box body text:

| **Do this** | **Don't do this** |
|---|---|
| If this workplace is deleted, it can't be recovered. | Are you sure you want to delete this workspace? |
| If this playbook is deleted, the following objects will no longer be available: | Please confirm that you want to delete this playbook and all of the objects in it. |
| Your changes won't be saved if you leave the workflow now. | If you leave this workflow, your changes won't be retained. Is this what you want to do? |

#### Button text

Create button text that helps a user decide whether to complete or revert their action. See the guidelines in [Button labels](#button-labels) on this page.

### Success messages

Success messages appear after a user completes a significant action in the product UI. Success messages typically appear and disappear briefly, or they might function as a message that the user can dismiss.

When writing a success message, keep the message brief and don't write in complete sentences. Use the following guidelines:

- Use short phrases without terminal punctuation.
- Write affirmatively.
- Use passive voice.

The following table shows examples of what to do and what not to do when writing success messages.

| **Do this** | **Don't do this** |
|---|---|
| Updates saved | Your updates have been successfully saved.<br>You have successfully saved your updates. |
| File archived | The file has been archived.<br>HID has archived your file. |
| Copied to clipboard | You have copied the file to the clipboard. |

### Error and warning messages

When writing a user-facing error or warning message, clearly state the problem and what the user can do to resolve it. For field validation error messages, it's okay to state the action to resolve the problem without explicitly stating the problem because cues in the UI, like the positioning of the error next to the field and the color of the text, identify the problem.

When writing an error message, use these guidelines:

- Use complete sentences with terminal punctuation.
- Don't use "please".
- It's okay to use passive voice to avoid placing blame on the user.

The following table shows examples of what to do and what not to do when writing error messages:

| **Do this** | **Don't do this** |
|---|---|
| Username not found. Verify that the username is correct and try again. | You entered the wrong username. |
| Enter your email address. | Your email address hasn't been entered. |
| The maximum number of concurrent searches has been reached. Decrease the number of concurrent searches or increase search concurrency limits in limits.conf. | Max number of concurrent searches reached. |
| WARN DistributedPeerManager - Unable to distribute to peer named xxxx at http://xxxx:8089 because authentication failed. Make sure adequate system resources are available on the target server. | WARN DistributedPeerManager - Unable to distribute to peer named xxxx at uri http://xxxx:8089 because peer has status = "Authentication Failed". |
| The maximum number of search jobs has been reached. To reduce the number of search jobs, go to Job Inspector and delete unneeded jobs. | Max search jobs encountered. |
