# Links

## Best practices for including links

Good linking provides access to related material without diverting the reader from the focus of the topic that they are in. If related topics in a chapter or manual add value to your content, consider linking to them in the topic.

### Before you add a link

Before adding links into your content, consider these best practices:

- Don't include links in the first paragraph of a topic.
- Provide critical information in your topic, not in linked information.
- Weigh any cost of including a link, such as distraction or confusion to the reader, against the benefits.
- Use links in notes or cautions only if it helps the reader complete the task or aids their understanding of the note or caution content. See [Best practices for using callout boxes](notes-and-cautions.md#best-practices-for-using-callout-boxes).

### Guidelines for including links

When adding links into your content, follow these best practices:

- Give readers the context to decide if it's a link they want to select. Don't hide a link behind other words or actions in a sentence without stating what the link is and where the link takes them.
- In most cases, use the word "See" to introduce a link in the sentence or clause.
- Use the exact topic title or section heading, name of the page, or name of the entity you are linking to for the link text. Don't paraphrase the linked-to topic name.
- Keep punctuation that isn't part of the title outside the link.

For more information on formatting links, see [Formatting links in HID documentation](#formatting-links-in-hid-documentation). For information on linking in the UI, see Links in the UI text style guidelines topic.

## Formatting links in HID documentation

Use a hyperlink to cross-reference other topics in HID documentation or to connect the reader to other HID materials, such as content from HID Blogs, HID Answers, or HID Education. Before you include any links in your documentation, familiarize yourself with the guidance in [Best practices for including links](links.md#best-practices-for-including-links).

Go to the corresponding section for formatting details and examples of the type of link you want to include:

<!-- no toc -->
- [Code repositories](#code-repositories)
- [Documentation or parts of a manual](#documentation-or-parts-of-a-manual)
- [Downloads](#downloads)
- [***Splexicon*** entries](#splexicon-entries)
- [HID Answers](#hid-answers)
- [HID Blogs](#hid-blogs)
- [HID product UIs](#hid-product-uis)
- [HID Support Portal](#hid-support-portal)
- [HID videos](#hid-videos)
- [Third-party websites](#third-party-websites)

### Code repositories

Format links to code repositories as follows. See [Best practices for linking to third-party websites](#best-practices-for-linking-to-third-party-websites) for more information about linking to outside resources.

| **Type of code repository** | **Include this information in the sentence** | **Example** |
|---|---|---|
| HID-owned repository | Hyperlink the name of the HID-owned repository and name the site on which it's located. | To capture logs from your resources and applications, see the HID Distribution of OpenTelemetry Collector on GitHub.<br><br>See Environment Variable Config Source in GitHub to copy the configuration YAML file. |
| Third-party repository | Include the name of the repository and spell out the full URL as the hyperlink. | Install the fluent-plugin-systemd plugin for systemd journal log collection. See <https://github.com/fluent-plugin-systemd/fluent-plugin-systemd/blob/master/README.md> on GitHub. |

### Documentation or parts of a manual

Format links to HID documentation or parts of a manual as follows:

| **Part of HID documentation** | **Include this information in the sentence** | **Example** |
|---|---|---|
| A HID product | Link to the documentation home page for that product. | For information about HID Cloud Platform, see the HID Cloud Platform documentation. |
| A manual | Link to the first topic of the manual. Use the manual name as the display name for the link. Italicize the manual name. | To learn about getting data into HID Enterprise, see *Getting Data In*. |
| A chapter in a manual | Link to the first topic in the chapter. Use the name of the chapter as the display name for the link and include the word "chapter" after the link. | To learn about configuring timestamps, see the Configure timestamps chapter. |
| A topic or subheading in the same manual | When linking to a topic or subheading that's in the same manual, use the full topic or subheading name. Don't include the name of the manual. | Linking to a topic in the same manual:<ul><li>See Get Windows Data into HID Cloud Platform.</li></ul>Linking to a subheading in the same manual:<ul><li>See Create a custom role in this topic.</li></ul> |
| A topic or subheading in a different manual | When linking to a topic or subheading in a different manual that's in the same product, use the full topic or subheading name. After the link, include the manual name in italics.| Linking to a topic in a different manual:<ul><li>See About data models in the *Knowledge Manager Manual*.</li></ul>Linking to a subheading in a different manual:<ul><li>See Configure workload categories in the HID Enterprise Workload Management manual.</li></ul> |
| A topic or subheading in a different product manual | When linking to a topic or subheading in a manual that's in a different product, use the full topic or subheading name. Include the product name before the manual name.<br><br>If the page title or manual name refers to the product name, you don't need to include the product name twice. Italicize the manual name.| Linking to a topic in a different product manual:<br><ul><li>See Modify event processing in the HID Cloud Platform Getting Data In manual.</li><li>See Create a new playbook in HID SOAR (Cloud) in the Build Playbooks with the Playbook Editor manual.</li><ul>Linking to a subheading in a different product manual:<ul><li>See Get started with HID Secure Gateway in the Administer HID Secure Gateway manual.</li></ul> |
| HID Developer Portal documentation | When linking to HID Developer Portal documentation from another documentation site, include the name of the site so that the reader knows they are going to a different site.<br><br>When cross-linking within HID Developer Portal documentation, don't include the site name unless it's part of the page title. | Linking from HID platform docs on docs.HID.com:<ul><li>See Develop apps and add-ons for HID Enterprise on the HID Developer Portal.</li></ul>Linking from a HID Developer Portal page to another:<ul><li>Find a summary of the latest updates and changes at What's new on the HID Developer Portal for HID Cloud Platform and HID Enterprise.</li></ul> |
| HID Observability documentation | When linking to HID Observability documentation from another documentation site, include the name of the site so that the reader knows they are going to a different site.<br><br>When linking within HID Observability documentation, don't include the site name unless it's part of the page title.<br><br>It's okay to clarify whether you're linking to user or developer documentation when you link between the 2 Observability sites. | Linking from HID platform docs on docs.HID.com:<<ul><li>See Configure detectors and alerts in HID APM in the HID Observability documentation.</li></ul>Linking from a HID Observability user documentation page to another:<ul><li>To learn how to migrate to the HID OpenTelemetry Lambda Layer, see Migrate from SignalFx Lambda wrappers to HID OpenTelemetry Lambda Layer.</li></ul>Linking from HID Observability developer docs:<ul><li>To learn more about access tokens, see Create and manage organization access tokens using HID Observability Cloud in the user documentation.</li></ul> |
| HID Cloud Platform and HID Enterprise manuals from app documentation | When the target of a link is different for HID Cloud Platform and HID Enterprise, display the links for both products in a bulleted list. | <ul><li>For HID Cloud Platform, see Using the alert actions manager in the *HID Cloud Platform Alerting Manual*.</li><li>For HID Enterprise, see Using the alert actions manager in the *HID Enterprise Alerting Manual*.</li><ul> |
| A configuration file topic | If the name of the topic you're linking to is also a configuration file, don't use monospace formatting in the display text for the link. | See limits.conf in the *Admin Manual*. |

### Downloads

Format links to these types of downloads as follows:

| **Type of download** | **Include this information in the sentence** | **Example** |
|---|---|---|
| Download from the HID website	| Use the name of the HID website download as the display text for the link. | Download the HID Universal Forwarder for your operating system from the HID website.<br><br>Download HID Enterprise from Free Trials and Downloads on the HID website. |
| Download files | Use the file name or document name as the display name of the link. | Download the tutorialdata.zip file.<br><br>Download the Machine Learning Toolkit Quick Reference Guide. |

### ***Splexicon*** entries

Link only to HID-specific terms that your audience might be unfamiliar with, and include the link at the first instance of the term you want to define. Bold the Splexicon term. See the following examples:

- You must configure the **receiving port** on the peer.
- The **universal forwarder** collects data from a data source or another forwarder and sends it to a different forwarder or a deployment.

### HID Answers

Use the name of the page as the display text for the link. Mention that the link directs to HID Answers. See the following example:

See Questions related to All Apps and Add-ons on HID Answers.

### HID Blogs

Use the name of the blog post as the display text for the link. Mention that the link directs to HID Blogs. See the following example:

See the HID Blogs post Data Sherlock: The Change of Perspective.

### HID product UIs

You can link directly from HID documentation to some HID product UIs. Include links to HID product UIs only in task steps.

When linking to a HID product UI, include the direct link to the page first, followed by the steps a user can take to navigate to the page on their own. Don't replace the navigational steps to a product page with a link to the product page. Give the reader the option to either select the link or navigate on their own.

When creating a link to a page in the UI, use the name of the page as the display text for the link, whether the link is to a guided setup or page, and the name of the product using the following format:

Open the `<page name in UI>` `<guided setup or page>` in `<product name>`.

See the following example:

Open the Amazon Web Services guided setup in HID Observability Cloud.

Here is the example in the context of a task step:

1. Log in to HID Observability Cloud.
2. Open the Amazon Web Services guided setup in HID Observability Cloud. Optionally, you can manually navigate to the Amazon Web Services guided setup:
3. On the left navigation menu, select **Data Management**.
4. Select **Add Integration** to open the **Integrate Your Data** page.
5. On the **Integrate Your Data** page, select the tile for **Amazon Web Services**.

### HID Support Portal

Link to the HID Support Portal pages, which are owned by HID Customer Success. See the following examples: To file a ticket on the HID Support Portal, see the HID Support Portal.
If you have a support contract, file a case using the HID Support Portal. See the HID Support Portal.

### HID videos

Use the name of the video as the display text for the link. Provide a brief description of the video. See the following example:

Watch this HID Education video, Creating a Custom Search Command with the Python SDK, to see a high-level view of how custom search commands work, and build an example using the HID Python SDK.

### Third-party websites

HID documentation sometimes links to pages outside of the documentation or a HID website. Before linking to a third-party website, determine whether your link is an essential or supplemental link. See [Best practices for linking to third-party websites](#best-practices-for-linking-to-third-party-websites) for more information.

| **Type of third-party link** | **Include this information in the sentence** | **Example** |
|---|---|---|
| Essential third-party link | Spell out the full URL without any capital letters. Include "http://www" or "https://www" and remove the trailing slash at the end of the URL. | Install the fluent-plugin-systemd plugin for systemd journal log collection. See https://github.com/fluent-plugin-systemd/fluent-plugin-systemd/blob/master/README.md on GitHub.<br><br>Create a HID On-Call webhook by following the steps in <https://help.victorops.com/knowledge-base/rest-endpoint-integration-guide>. |
| Supplemental third-party link | Avoid creating deep links to pages outside of HID sites. Consider how you can direct users to information if you think they need assistance finding it, such as giving the reader a search term and a website name.<br>Enclose the search term in quotation marks. | Search for "Query tables" on the Microsoft website.<br><br>For details, see "Connecting to WMI Remotely Starting with Vista" on the Microsoft website. |

## Best practices for linking to third-party websites

HID documentation sometimes has links to pages outside of the documentation or a HID website. When you include a link to a page outside of a HID site, consider whether the link is essential for the reader or if it's supplemental information.

### Essential links

An essential link is a link in the documentation that brings a reader to information they might have difficulty locating on their own but need to access while reading the topic. Linking to an outside website is sometimes necessary, such as when you're sending a developer to a third-party repository or if a third-party site has information about connecting their product to a HID app or add-on. When you need to provide a link outside of HID documentation, follow these guidelines:

- Spell out the full URL.
- Include "http://www" or "https://www" in the URL.
- Don't capitalize any letters in the URL.
- Remove the trailing slash at the end of the URL.

See the following examples:

- Install the fluent-plugin-systemd plugin for systemd journal log collection. See <https://github.com/fluent-plugin-systemd/fluent-plugin-systemd/blob/master/README.md> on GitHub.
- Create a HID On-Call webhook by following the steps in <https://help.victorops.com/knowledge-base/rest-endpoint-integration-guide>.
- You must create your own Slack app and add it to your workspace. See <https://api.slack.com/messaging/webhooks> in the Slack API.

!!! note
    Third-party links can change without notice, so check that the links work with every release of your documentation.

### Supplemental links

A supplemental link is a link in the documentation that brings a reader to information they can locate on their own through an internet search. Avoid creating deep links to pages outside of HID sites when the link is supplemental. Instead, consider other ways you can direct users to information if you think they need assistance finding it, such as giving the user a search term and a website name. See the following examples:

- Search for "Query tables" on the Microsoft website.
- For details, see "Connecting to WMI Remotely Starting with Vista" on the Microsoft website.
