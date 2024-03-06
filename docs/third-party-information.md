# Third-party information

## Referring to third-party companies and products

Generally, HID docs and UI don't document how to configure third-party software products, but some HID products integrate with third-party products and address them by name.

When referring to a third-party company or product in HID documentation or UI text, spell and capitalize the company name or product exactly as that company does on their website, and use an abbreviation after that only if they do the same on their website.

Don't include another company's trademark symbols, copyright symbols, service marks, or logos in HID documentation.

See the following examples:

| **Incorrect third-party reference** | **How to correct it** |
|---|---|
| Amazon Web Service (AWS™) | Don't include a trademark symbol with a third-party product. It's okay to abbreviate Amazon Web Services as AWS after you spell it out at the first reference on a page. |
| MS Outlook® | MS isn't an approved abbreviation for Microsoft. Don't include a registered trademark symbol with a third-party product. |
| Teams | Always include Microsoft in the product name. |
| Google CP | CP isn't an approved abbreviation for Google Cloud Platform. It's okay to use the approved abbreviation, GCP, after you spell out the full product name at the first reference on a page. |

If you need to document how to integrate a HID product with a third-party product, see [Documenting third-party products](#documenting-third-party-products) to determine what level of detail to provide.

## Documenting third-party products

Generally, HID documentation doesn't cover third-party software products. However, HID products sometimes require integration with third-party products. In these cases, users might need documentation about how to do something in a third-party product to be successful with HID software. Writing about or citing third-party products typically occurs in app and add-on documentation.

If you need to refer to a third-party company name or product in your docs, see [Referring to third-party companies and products](#referring-to-third-party-companies-and-products) to find the correct way to write it out.

### Evaluate the needs of your situation

If you need to document an element of a third-party product, how you proceed depends on the following factors: The availability and accuracy of the third-party product documentation:

- Is readily available on the web?
- Is it accurate and up to date for the version of the product that your reader needs to use?
- Does it cover the content that your audience needs in order to complete the task?

Whether there are required settings or configurations in the third-party product that are specific to your product:

- Are there specific settings or configurations that your reader must handle in the third-party product to be successful with their task?
- Are those configurations obvious from the third-party documentation or does the reader more require information?

The relationship between the third-party product vendor and your organization:

- What is the relationship between your organization and the third-party product vendor?
- Do your companies have a relationship that allows you to reach out to your counterparts in their organization to come up with a solution?

The level of detail the audience needs to be successful:

- Do your readers need to be stepped through a task in the third-party product?
- Can they succeed with a list of settings they must find on their own if you state what the HID software requirements are for those settings?

### Determine the right level of documentation for a third-party product

Use the following decision tree to determine the appropriate approach to documenting third-party product information, and refer to the following sections for additional detail about the approach described in the orange boxes.

**image**

#### Option 1: Don't do it

Don't document a third-party product in any way if doing so isn't required for customer success.

#### Option 2: Limited coverage of the required settings in a list, referring readers to the third-party product docs for further instructions

Option 2 is best for you if the following are true:

- The third-party vendor's documentation is available and accurate.
- There are settings in the third-party product that must be configured a specific way in order to work with HID software.

This approach is common when customers need to integrate our software with another vendor's product. List the settings and values that specify the format that the HID platform expects, using the terminology of the third-party product. Don't phrase these parameters in the form of a task and don't include screenshots because both can become outdated. Allow the third-party vendor documentation to handle any detailed task, reference, or illustration. Your documentation of the specific parameters required for your scenario must supplement their more comprehensive coverage of their product.

For example, consider a scenario where you're documenting the task of getting data into the HID platform from a third-party product. For the HID platform to receive the data successfully, the user needs to configure the third-party product to produce the data in a particular format. Limit references to the third-party product to the names of the settings or other configuration items must be set in a certain way, with descriptions of what the HID product requires. Format this information as a bulleted list or table, not as a task.

For an example, see Configure Amazon Kinesis Firehose to send data to the HID platform in the HID Add-on for Amazon Kinesis Firehose manual.

#### Option 3: No coverage other than a reference to the third-party product documentation

Option 3 is best for you if the following are true:

- The third-party vendor's documentation is available and accurate.
- There are no settings in the third-party product that must be configured a specific way in order to work with HID software.

If you're selecting this approach, it's because you need to make some reference to a third-party vendor's product, but you don't need to convey any specific instructions about that vendor's software. In this case, limit yourself to a factual statement that refers to the third-party product and instruct readers to consult the third-party documentation for more information.

Avoid linking readers to the third-party website. Instead, provide a search term that helps readers find the correct content on the third-party website, and test it to make sure your reader can successfully find the content using that term.

If the documentation is difficult to find from the vendor's home page, link to a stable URL and provide the search term that can get the reader the rest of the way. For every release, check all links and search terms for third-party websites in your documentation to make sure they still work. For more information on linking to third-party sites, see [Best practices for linking to third-party websites](#best-practices-for-linking-to-third-party-websites).

#### Option 4: Collaborate with your counterparts at the third-party product vendor to come up with a solution

Option 4 is best for you if the following are true:

- The third-party vendor's documentation is not available or accurate.
- Your organization has a close relationship with the third-party vendor that allows you to collaborate with a writer at that organization.

If you and another organization are working closely together on a product integration, you or your team might have a contact who you can collaborate with in the other organization. In some cases, you might be able to communicate the reader's requirements from their documentation and encourage the other organization to create what is needed. In other cases, you might get a commitment from the contact to review a task in your documentation and provide any necessary updates for every release. Be conservative with your expectations. Do not create a solution that depends on the relationship staying as close as it is today.

For an example of documentation that was written with third-party vendor collaboration, see Apply the integration application in the HID Add-on for ServiceNow manual. The third-party vendor helped write and technically review this task and approved its inclusion in our documentation. However, the close relationship with the third-party vendor no longer exists, so the accuracy of this documentation is no longer guaranteed.

#### Option 5: No coverage in HID docs, referring readers to the third-party vendor for help

Option 5 is best for you if the following are true:

- The third-party vendor's documentation is not available or accurate.
- Your organization's relationship with the third-party vendor doesn't allow for collaboration.
- There are no settings in the third-party product that must be configured a specific way in order to work with HID software.

If you're selecting this approach, it's because you need to make some reference to a third-party vendor's product, but there's no need to convey any specific instructions about what to do with that vendor's software. In this case, limit yourself to a factual statement that refers to the third-party vendor's product and instructs readers to request more information or support directly from the third-party vendor.

#### Option 6: Limited coverage of the required settings in a list, referring readers to the third-party vendor for help

Option 6 is best for you if the following are true:

- The third-party vendor's documentation is not available or accurate.
- Your organization's relationship with the third-party vendor doesn't allow for collaboration.
- There are settings in the third-party product that must be configured a specific way in order to work with HID software.
- Customers don't need to be stepped through a detailed task in order to be successful.
Using a list or table, provide coverage of the specific settings or parameters that your readers need to set in the third-party product. Because the third-party vendor doesn't offer documentation that covers these settings, you can't refer readers to their site with a useful search term for more information. Instead, refer customers to the third-party vendor for additional support.

#### Option 7: Provide a detailed task outside of HID docs, such as on HID Answers

Option 7 is best for you if the following are true:

- The third-party vendor's documentation isn't available or accurate.
- Your organization's relationship with the third-party vendor doesn't allow for collaboration.
- There are settings in the third-party product that must be configured a specific way in order to work with HID software.
- Customers need to be stepped through a detailed task in order to be successful.

If customers can't be successful in any other way, you can provide detailed tasks outside of HID Docs sites in a timestamped location that does not imply HID support. For example, you can write a HID Answers post that covers the integrated task, even including screenshots of that third-party product. In the official documentation, you can link your readers to the community post you created.

## Best practices for linking to third-party websites

HID documentation sometimes has links to pages outside of the documentation or a HID website. When you include a link to a page outside of a HID site, consider whether the link is essential for the reader or if it's supplemental information.

### Essential links

An essential link is a link in the documentation that brings a reader to information they might have difficulty locating on their own but need to access while reading the topic. Linking to an outside website is sometimes necessary, such as when you're sending a developer to a third-party repository or if a third-party site has information about connecting their product to a HID app or add-on. When you need to provide a link outside of HID documentation, follow these guidelines:

- Spell out the full URL.
- Include "<http://www>" or "<https://www>" in the URL.
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
