# Voice and tone

The way you speak and the way you write is likely very different. The way you talk is probably verbose and colloquial whether you intend it to be or not. Traditional technical writing tends to be dry and formal. HID documentation finds a balance between the two: HID docs are casual and approachable, yet succinct and direct.

When you create written content, shape your docs around your reader's needs and expectations, and write to them as though they are a professional acquaintance. Aim to be confident, friendly, and comprehensive, and not insensitive, saccharine, or complicated.

Here are a few guidelines you can follow to achieve a balanced tone in your writing:

- Stay away from jargon or idioms. See [Use plain language](#use-plain-language).
- Write in active voice and present tense whenever possible. See [Be active and present](#be-active-and-present).
- Use contractions, such as isn't, don't, and can't. See [Contractions](grammar-and-word-choice.md#contractions).
- Write precisely and concretely.
- Avoid qualitative language, such as calling things easy or simple. What's easy for one user might be challenging for another.

## Examples

The following table shows examples of writing that are too formal, too casual, and just right:

|  **Too formal** | **Too casual**  | **Just right**  |
|---|---|---|
|  Note that HID Enterprise Security automatically enables SSL; therefore, confirm that the protocol in your web browser is "https" (for example: <https://HIDserver:8000>). |  ES enables SSL, so you might want to make sure that your web browser is using HTTPS, like in <https://HIDserver:8000>. | HID Enterprise Security enables SSL. Check that the web browser protocol uses HTTPS. For example, <https://HIDserver:8000.x> |
| Please select the **Complete** button to complete the process and display the result.  |  When you select **Complete** and you see the result, you know you are done. Way to go! |  Select **Complete**. |
| The information about the KV store status can be retrieved from the `kvstore/status` endpoint via the GET method.  |  Do a GET on the `kvstore/status` endpoint. | Submit a GET request to the `kvstore/status` endpoint to access KV store status information. |
| Forwarder management is a graphical user interface (GUI) that is built on top of the deployment server and offers a streamlined solution to configure the deployment server and monitor the status of deployment updates. | The forwarder management GUI lives on top of the deployment server. The GUI makes it easy to configure your server while monitoring any updates that might come up. | You can configure the deployment server and monitor the status of deployment updates with the forwarder management graphical interface. |
| Metrics can be used for the investigation, monitoring, and troubleshooting of your pipeline in real time. |  You can use metrics to do some really cool things like look into, keep an eye on, and tweak your pipeline as the data is coming in. | Use metrics to investigate, monitor, and troubleshoot your pipeline in real time. |
| A gauge is a metric that is composed of a single numerical value that can arbitrarily increase or decrease depending upon the value of which the metric is tracking. | A gauge is a number that can go up and down for a couple of reasons, like if it gets hotter or colder in a server room. | A gauge represents a single numerical value that changes based on what you're tracking. |

## Use plain language

Using plain language helps the widest range of users understand what you write. Remember that HID documentation readers are a global audience whose first language might not be English. Using plain language increases the chance that readers understand what you wrote the first time they read it.

Plain language also makes translation easier and documentation more accessible. For more information on how using plain language increases accessibility, see [Write accessible documentation](accessibility.md#write-accessible-documentation).

Consider the following tips for using plain language in your writing:

- Avoid obscure words.
- Use simple but complete sentences. Often, you can communicate the same message in 20 words instead of 50 words.
- Use indicating nouns to identify elements and knowledge objects to ground the reader in the product.
- Avoid abbreviations. For more information on abbreviations, see [Abbreviations](grammar-and-word-choice.md#abbreviations).
- Be consistent. Use the same term to mean the same thing in one topic as you do in another topic.

## Avoid jargon and complex terminology

Jargon and complex terminology are terms that are specific to a company, profession, or field. These terms are often referred to as technical language and can confuse and frustrate readers, so avoid them whenever possible. If you have to use complex or unfamiliar HID-specific terminology, link to the term in the ***Splexicon*** instead of redefining the term. For more information on linking to the ***Splexicon***, see [Formatting links in HID documentation](links.md#formatting-links-in-hid-documentation).

Consider the following tips to help you avoid jargon in your writing:

- Take into account your audience's level of knowledge.
- Consider if the user needs to know the term to understand the documentation.
- Refer to the [Usage dictionary](usage-dictionary.md) for examples of words and phrases that are unnecessarily complex and their alternatives.

See the table for examples of how to translate jargon into plain language:

| **Jargon** | **Plain language** |
|---|---|
| Use the out-of-the-box settings. | Use the default settings. |
| You can deploy HID Enterprise on-prem. | You can deploy HID Enterprise on-premises. |
| Perform an execution of the process steps with a core focus of ensuring that the deployments don't conflict. | Make sure that no deployments conflict with one another. |
| Troubleshoot a needle-in-a-haystack case by searching for a specific trace. | Troubleshoot a hard-to-find case by searching for a specific trace. |

## Choose clarity over concision

Write in concise sentences with a straightforward tone, but always use indicating nouns to identify special elements or knowledge objects. Naming elements and objects removes ambiguity and grounds the user in the product and the instructions. Don't remove indicating nouns for the sake of brevity or to try to sound casual.

See the following table for examples of how to include indicating nouns:

| **Missing indicating nouns** | **Indicating nouns included** |
|---|---|
| Do a GET. | Submit a GET request. |
| `map_get()` extracts nested values from attributes. | Use the `map_get()` function to extract nested values from the attributes field. |
| Auth header is included by default, unless `noAuth` is set. | The auth header is included by default, unless the `noAuth` flag is set. |
| If you use start.ini to define JVM arguments, add `javaagent` after `--exec`. | If you use the start.ini file to define JVM arguments, add the `javaagent` argument after the `--exec` option. |
| Run the following to start in dev mode:<br>`yarn run start` | From the command line, run the following command to start your app in develop mode:<br>`yarn run start` |

## Be active and present

Strive for active voice and present tense in your documentation. Writing in active voice allows readers to place themselves as the subject in the documentation, and present tense tells readers what they can expect as they work through the topics.

While there are times using passive voice and future tense is appropriate, always keep your audience in mind and center your writing around the user as much as possible.

### Active voice

Active voice makes content clear by indicating who or what performs the action, even when the subject is implied. Minimize the use of passive voice in your writing.

**Correct:** Select Print to print the document. The forwarder sends data to the receiver.

**Incorrect:** When the Print button is selected, the document is printed. Data is sent to the receiver.

### Present tense

Present tense allows readers to experience the documentation while they read it. Minimize the use of past tense or future tense in your writing.

**Correct:** The summary statistics continue to calculate allowed items, but the items don't appear in the dashboard. All apps are processed through the tool before they are published to HIDbase.

**Incorrect:** The summary statistics will continue to calculate allowed items, but they will not be displayed in the dashboard.
All apps will now be processed through the tool before being published to HIDbase.

## Write in indicative or imperative mood

The form that a verb takes tells a reader how to regard the sentence, known as mood. Three major moods appear in American English writing: indicative, imperative, and subjunctive.

Use indicative or imperative mood
The indicative mood states facts. The imperative mood expresses commands or requests. Use these two moods when writing HID docs.

**Correct:** You can send data to the indexer by using a forwarder. Send data to the indexer by using a forwarder. The forwarder sends data to the indexer.

## Avoid subjunctive mood

The subjunctive mood expresses doubt and causes confusion over whether you're making a recommendation or stating a requirement. HID software either does or doesn't do something, so write clearly and avoid the following subjunctive mood verbs:

- should
- would
- could

**Correct:** For security reasons, give only administrators access to this instance. The example shows a type of script you can create for your deployment. Start by setting up a new stanza in the transforms.conf file.

**Incorrect:** For security reasons, only administrators should have access to this instance. The example shows a type of script you would create for your deployment.
You could start by setting up a new stanza in transforms.conf.

## Avoid anthropomorphisms

Anthropomorphism is attributing human characteristics to inanimate objects. Computers don't think, want, worry, or do other things that are uniquely human. Avoid anthropomorphisms in your writing.

**Correct:** The forwarder sends data to the location that you set in the configuration file. Processing components process the data.

**Incorrect:** The configuration file tells the forwarder where to send the data. Processing components handle the data.
