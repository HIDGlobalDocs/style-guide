# Titles and headings

## Manual names, topic titles, and section headings

Succinct and descriptive names for manuals, chapters, topics, and sections let a user know what they can expect to find in the content. Titles that include the product name tell readers which product they are in when they land on your topic from a search. Clear headings support the reader's ability to locate information on the page quickly.

### Best practices

- Include the product name in the topic title. If the product name is too long, use an approved abbreviation.
- Write titles and headings using words that are short, descriptive, and specific.
- Focus titles and headings around what a user can do with the product. Stay away from creating titles and headings that describe a feature.
- Remove vague terms or phrases in titles and headings, such as "Other", "Miscellaneous", "Introduction", or "Before you begin" and use definitive language instead.
- Don't use special formatting in headings, such as monospaced font or italics.

### Name your manual

Create your manual name using an imperative statement with the product name. If the product name is very long, you can use the product abbreviation at the end of the title, as long as the abbreviation is approved.

Avoid terms such as "Guide" or "Manual" in the manual name, and find a descriptive verb to accompany the product in the manual name instead. You can also use a noun that describes the content, such as Release Notes, Scenarios, Tutorial, and API Reference.

Use headline-style capitalization for manual names. See [Capitalization](capitalization.md).

When you refer to a manual name in HID docs, format the manual name in italics. See [Formatting reference](formatting-text.md).

#### Manual name examples

The following table shows examples of clear and descriptive manual names:

| **A clear, descriptive manual name** | **What makes this manual name good** |
|---|---|
| Administer HID Enterprise Security | This name is a better option than something like "Admin Guide" because it is action-oriented and names the specific product it applies to. |
| Install and Upgrade HID Enterprise Security | This name is a better option than something like "Installation Guide" because it lets a reader know that it contains both installation and upgrade content for HID Enterprise Security. |
| Get Data Into HID User Behavior Analytics | This name is a better option than something like "Getting Data In" because it's imperative in tone for a specific product. |
| Use HID Enterprise Security Dashboards | This name is a better option than something like "Dashboard Manual" because it is action-oriented and names the particular product. |
| Integrate the HID App for Infrastructure with ITSI | This name is a better option than something like "Integrate SAI" because it tells the reader which products they can integrate. |
| Search and Visualize Data with HID NLP | This name is a better option than something like "Search Data" because it includes visualizations, which is a keyword for the HID NLP product. |

### The order of headings

Refer to the following terms when you create your manual:

| **Heading level** | **What it means** |
|---|---|
| H1 | The topic title |
| H2 | Subheading |
| H3 | A subsection in a subheading |

Use only one H1 per topic.

Follow the correct order of heading levels in HID docs: H1, H2, and then H3. Don't follow an H1 with an H3. Don't place content deeper than an H3.

### Headings and text together

Make sure that text follows every topic title or section heading.

In most cases, don't follow a topic title or heading with another heading, a list, a table, or an image. There are times, however, when it's acceptable to follow an H1 with an H2 and have no intervening text, or to follow an H2 with an H3 and have no intervening text:

- In a reference topic, such as a glossary of terms or commands.
- In a task, when the text between the heading and the numbered task steps merely repeats the heading.
Everywhere you can, provide important information the reader needs to know in the text between headings. Always make sure that your headings are useful and descriptive.

### Name your topic or sections

Include the product name in the topic title. If the product name is too long, use an approved abbreviation. You don't need to include the product name in every H2 and H3.

Use sentence-style capitalization for chapter names, topic titles, and section headings. See [Capitalization](capitalization.md).

Don't use numbers in headings to indicate a sequence unless you're listing parts of a tutorial. Only use numbers in a heading if they are part of a name, like "SPL2". See [Numbers in headings](numbers.md#numbers-in-headings).

As a guideline, use the following moods and phrases in your titles and headings for the type of content you're writing:

| **Type of content** | **Mood or phrase to use** | **Examples** |
|---|---|---|
|Task information | Imperative mood. Use command verbs in the present tense, such as "edit" or "modify". | Correct<ul><li>Configure correlation searches</li></ul>Incorrect<ul><li>Configuring correlation searches</li></ul> |
| Reference information | Noun phrase | Correct<ul><li>Search commands</li></ul>Incorrect<ul><li>Using search commands</li></ul>Correct<ul><li>ITSI REST API reference</li></ul>Incorrect<ul><li>Using the ITSI REST API reference</li></ul> |
| Conceptual information | Gerund phrase or noun phrase | Correct<ul><li>Installing HID Enterprise</li></ul>Incorrect<ul><li>How to install HID Enterprise</li></ul>Correct<ul><li>The redistribute command</li></ul>Incorrect<ul><li>Use the redistribute command</li></ul> |
| Scenario-based content | Third-person point of view. Use indicative verbs, such as "schedules" or "investigates". | Correct<ul><li>Scenario: Kai schedules a weekend shift</li></ul>Incorrect<ul><li>Use case: Schedule a weekend shift</li></ul>Correct<ul><li>Scenario: Sasha investigates performance issues</li></ul>Incorrect<ul><li>Investigate performance issues | 

#### Topic title and section heading examples

The following table shows examples of good topic titles and section headings:

| **Original title** | **A clearer, more descriptive title** |
|---|---|
| Import entities | Import entities into ITSI from a CSV file |
| Use setup pages | Enable first-run configuration with setup pages in HID Cloud Platform or HID Enterprise |
| About the HID App for CEF | How the HID App for CEF works |
| Configure inputs | Configure inputs for the HID Add-on for AWS |

### Name your topic in the TOC

Some authoring platforms allow you to use a name for your topic in the table of contents that is different from the topic title. It's okay to abbreviate long topic titles in the TOC by leaving out the product name, but don't change the primary verb and object of the title. If the name in the TOC is too different from the topic title, readers aren't sure if they're in the right topic when they select one in the TOC.

Mood and phrasing cue the reader into the type of content they're about to read, so don't change the mood or phrasing of the topic title in the TOC. For example, if the topic title is written in the imperative mood, don't rephrase the title as a noun phrase or gerund in the TOC.

The following table shows examples of topic titles and correct and incorrect examples of TOC names:

| **Topic title** | **Correct example of TOC name** | **Incorrect example of TOC name** |
|---|---|---|
|Install the Browser RUM agent for HID RUM | Install the Browser RUM agent | Install the instrumentation |
| Configure the HID Browser RUM instrumentation | Configure the instrumentation | Configuring the instrumentation |
| Manually instrument browser-based web applications | Manually instrument the application | Manual instrumentation |
| Add navigation to an app in HID Cloud Platform or HID Enterprise | Add navigation to an app | Adding navigation |

### Context-friendly headings

Write headings that users can understand without the context of the surrounding topics or sections. For example, don't include numbered steps in titles or headings, such as "Step 5: Move the cursor." A supertask might be a better way to organize your content than to include numbered steps in the title or heading.

### Can I write a title or heading in the form of a question?

You can write topic titles or section headings in the form of a question, but use this form sparingly.
