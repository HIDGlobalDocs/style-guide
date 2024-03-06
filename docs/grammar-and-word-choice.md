# Grammar and word choice

## Abbreviations

Don't use common abbreviations, such as a.k.a., e.g., etc., i.e., and vs. in documentation and UI text. Instead, use precise language and state what you mean. See the [Usage dictionary](usage-dictionary.md) for terms to use instead of abbreviations.

For keyboard shortcuts, abbreviate the names of keys only if you have a space constraint, otherwise spell out letter keys and key names. See [Writing keyboard shortcuts in HID docs](#writing-keyboard-shortcuts-in-a-confined-space).

It's okay to abbreviate a unit of measurement in text. See [Measurements](numbers.md#measurements).

## Acronyms

Always spell out a full term at first use on every page before you refer to it as an acronym or initialism. Add the acronym or initialism in parentheses after the full name.

| **Correct** | **Incorrect** |
|---|---|
| Use the HID Search Processing Language (SPL) to search your data. | Use SPL (the HID Search Processing Language) to search your data. |

### Capitalizing acronyms

Capitalize all letters in an acronym or initialism, including file name extensions and file types that you use as adjectives. Don't use periods with acronyms or initialisms when they stand alone in text.

| **Correct** | **Incorrect** |
|---|---|
| CSV file<br>HTTP protocol<br>JSON file<br>Upload the docs.pdf attachment. | c.s.v. file<br>http protocol<br>json file<br>Upload the docs.PDF attachment. |

See more examples in File name extensions and File types in the [Usage dictionary](usage-dictionary.md).

### Match acronyms to its spelled-out version

Don't use an acronym or initialism if it doesn't closely match the words it refers to.

| **Avoid** | **Use** |
|---|---|
| Use a tool like Volume Shadow Copy Services (VSS). | Use a tool like Volume Shadow Copy Services. |

### Common acronyms

Consider your audience's level of understanding and use your best judgment for commonly accepted abbreviations, such as REST and API.

### Third-party acronyms

See [Referring to third-party companies and products](third-party-information.md#referring-to-third-party-companies-and-products) for information on using third-party acronyms and initialism.

### Abbreviating time and measurements

See [Dates](numbers.md#dates) and [Time](numbers.md#time) for date and time abbreviations and [Measurements](numbers.md#measurements) for abbreviating rates of measurement.

## American English spelling and phrases
Write in American English. The dictionary of choice for HID documentation is [Merriam-Webster](<https://www.merriam-webster.com/>){:target="_blank"}, so consult the dictionary if you question your spelling.

Avoid Latin and British abbreviations, spelling, and phrases, such as e.g., colour, and full stop, in your documentation. See the [Usage dictionary](usage-dictionary.md) for acceptable terms to use instead.

## Contractions

HID documentation is informal in tone, so you can use contractions in the present tense, such as "isn't", "don't", and "can't".

Don't use contractions for the past tense, such as "didn't".

If you can't rewrite a future-tense sentence into present tense, it's okay to use contractions, such as "won't". For more details about tenses, see [Be active and present](voice-and-tone.md#be-active-and-present).

Don't put apostrophes in brand names, company names, or products to make them possessive. For more information, see [Possessive names and terms](#possessive-names-and-terms).

## Example names and domains

If you need to create a fictitious name, email address, domain name, phone number, or IP address in your docs, create an example that adheres to the following guidance.

### Names

Most topics in HID documentation use the second-person singular pronoun, "you" and "your", to address a single user directly. If you have to refer to someone in the third person, create a gender-neutral fictitious name that's sensitive to culture, religious affiliation, holidays, traditions, politics, and business. Make sure that the name you create reflects the wide range of names used around the world.

Don't use a fictional character that's currently in copyright, your own name, or the name of friends or family members as an example name.

#### Given names

It's okay to use a first name only for your documentation, such as in a scenario or a walkthrough. See the following examples of names that meet this guidance:

- Alex
- Deepu
- Ikraam
- Kai
- Morgan
- Skyler
- Wei

#### Family names

Create a fictional surname if you need a first and last name, such as in example UI text fields or search results. See the following examples:

- Charlie Garcia
- Nyah Aamadu
- Sasha Patel
- Taylor Zhang

#### Pronouns for fictitious names

Use gender-neutral third-person pronouns, such as "they", "their", and "them", to accompany the fictitious name. See [Gender-neutral pronouns](#gender-neutral-pronouns).

#### Email addresses

If you need a fictitious email address for an example, use a name that follows the guidance in the Names section. Never use your own name or the name of friends or family members in an example email address.

Use Buttercup Games, a fictitious online store created by HID, as the email domain. See the following examples:

- alex@buttercupgames.com
- buttercup@buttercupgames.com
- info@buttercupgames.com

In cases where it doesn't make sense to use Buttercup Games as the email domain, use the @example.com suffix.

#### Domain names

If you need a fictitious domain name for an example in your docs, see the following table of domains:

| **Domain** | **Redirects to** |
|---|---|
| https://www.example.com | Example domain page |

#### Phone numbers

If you need a fictitious phone number for an example in your docs, use a North American phone number in the range +1-555-555-0100 through +1-555-555-0199. The North American Numbering Plan set aside this range of phone numbers to use in examples and in fiction.

If you need a fictitious international phone number for an example in your docs, you can use the fictitious Australian phone number of +61-2-5550-9988.

Never use a real phone number as an example.

#### IP addresses

The Internet Engineering Task Force (IETF) and the Internet Assigned Numbers Authority (IANA) have reserved various IP addresses specifically for documentation needs.

##### IPv4 addresses

If you need a fictitious IPv4 address for an example in your docs, use an IP address in one of the following ranges:

| **Subnet** | **IP address range** |
|---|---|
| 192.0.2.0/24 | 192.0.2.0 to 192.0.2.255 |
| 198.51.100.0/24 | 198.51.100.0 to 198.51.100.255 |
| 203.0.113.0/24 | 203.0.113.0 to 203.0.113.255 |

Find more information in the IETF memo at [https://datatracker.ietf.org/doc/html/rfc5737](<https://datatracker.ietf.org/doc/html/rfc5737>).

##### IPv6 addresses

If you need a fictitious IPv6 address for an example in your docs, use an IP address in the 2001:db8::/32 range.

For example, use 2001:0db8:ffff:ffff:ffff:ffff:ffff:ff00/120 as the subnet and 2001:0db8:ffff:ffff:ffff:ffff:ffff:ff99 as the IP address.

Find more information in the IETF memo at [https://datatracker.ietf.org/doc/html/rfc3849](<https://datatracker.ietf.org/doc/html/rfc3849>).

### Keyboard shortcuts

Follow these guidelines when writing keyboard shortcuts in HID documentation.

#### Operating system keyboard shortcuts

If the action a user takes on a keyboard is a well-known operating system command, focus on the outcome rather than the keyboard shortcut and use device-agnostic language. See [Use device-agnostic language](bias-free-communication.md#use-device-agnostic-language).

| **Correct** | **Incorrect** |
|---|---|
| Copy your token. | Select Control+C to copy your token. |

#### HID product keyboard shortcuts

If you're writing a keyboard shortcut that's specific to a HID product, follow these guidelines:

- Use initial capitalization, plus ( + ) signs, and no spaces between key names and symbols.
- Use capital letters to represent letter keys.
- Don't format keys in bold or monospace font.
- Spell out the name of the keys where space allows.
- Don't use symbols instead of key names.

See the following examples:

| **Correct** | **Incorrect** |
|---|---|
| Command+Shift+Z<br>Control+1 | `Cmd - B`<br>+ Shift + Esc |

#### Writing keyboard shortcuts in a confined space

If you're working within a space constraint, such as in a UI or a table column, it's okay to abbreviate key names like Ctrl, Cmd, Del, and Esc.

#### Differences in Mac and PC keyboards

There are differences between Mac keyboards and PC keyboards, which are used for Windows and *nix, such as the Command, Control, Option, Alt, and Windows keys. Include both keyboard shortcut variations as a sentence or a table. See the following examples:

| **Correct as a sentence** | **Correct as a table** |
|---|---|
| Select Control+N for Mac or Alt+N for Windows or *nix. | You can use the following keyboard shortcuts in the playbook editor: |

| **Action** | **Mac | **Windows or *nix** |
|---|---|---|
| Add block panel |Command+B | Control+B |
| Add prompt block | Command+8 | Control+8 |
| Auto arrange playbook | Command+Shift+F | Control+Shift+F |
| Toggle Python editor | Command+E | Control+E |
| Show hotkeys | Command+? | Control+? |

#### Plurals in parentheses

Don't write a lowercase s or es in parentheses, "(s)" or "(es)", after a noun to indicate both singular and plural. Choose the best option for your documentation. In most cases, using the plural works best for understanding the sentence.

If it's important to include both singular and plural, try including the phrase "one or more".

| **Correct** | **Incorrect** |
|---|---|
| The endpoint returns the current webhook key.<br>The endpoint returns the current webhook keys.<br>The endpoint returns one or more of the current webhook keys.<br>The endpoint returns all of the current webhook keys. | The endpoint returns the current webhook key(s). |

For acceptable uses of parentheses in your writing, see [Parentheses](punctuation-and-symbols.md#parentheses).

#### Possessive names and terms

Don't use an apostrophe to make product names, company names, or trademarked terms possessive.

| **Correct** | **Incorrect** |
|---|---|
| The dashboard shows data pulled from the HID Enterprise internal log files.<br>Submit a case using the HID Support Portal.<br>The Search function has robust capabilities. | The dashboard shows data pulled from HID Enterprise's internal log files.<br>Submit a case using HID's Support portal.<br>Search's capabilities are robust. |

For acceptable uses of apostrophes, see [Apostrophe](punctuation-and-symbols.md#apostrophe).

### Prepositions

You can use prepositions to orient users to a location when writing HID documentation. Use your best judgment to determine what sounds best.

#### Choosing the best preposition

Use "into" in the context of getting data into a HID product. Otherwise, choose any preposition that fits the context of the sentence and doesn't cause confusion for the reader. The following list shows a number of acceptable options:

| **term** | **acceptable option(s)** |
|---|---|
| from | from the command line<br>from the Settings menu |
| in | in HID Cloud Platform<br>in a folder<br>in the Search bar |
| into | Get data into HID Enterprise. |
| on | on a forwarder on an indexer<br>on the Dashboard toolbar on your web browser |
| within | within a multi-clustered environment | 

You can also choose another word, such as "over", "across", "through", or "with" if that is more accurate:

- over large datasets
- across your deployment servers
- through a custom event
- with a token

Avoid Latin phrases in HID documentation, so don't use "via" as a preposition. See [American English spelling and phrases](#american-english-spelling-and-phrases).

#### Placing prepositions in a sentence

Place the preposition where it makes the sentence easiest to comprehend. It's okay to use a preposition at the end of a sentence. See the following examples:

- Determine which deployment you're running your app in.
- Define the assets that admins interact with.
- This field represents the protocol that the rule is written for.

### Pronouns

Pronouns replace nouns. When you use pronouns in your writing, make sure that the pronoun correctly refers to the noun it replaces, known as its antecedent.

#### Gender-neutral pronouns

Write for inclusivity and don't make assumptions about sex or gender. When you write HID documentation, avoid gender-specific and sexist language.

Most of the topics in HID documentation use the second-person singular pronoun, "you" and "your", to address a single user directly. If you have to write in the third person or refer to someone in the third person, make sure that you choose gender-neutral third-person pronouns, such as "they", "their", and "them".

In HID documentation, it's acceptable to use a plural pronoun with a singular antecedent when you refer to people. Use third-person-plural pronouns when you refer to a person. Don't write "him or her" or "his or hers".

| **Correct** |
|---|
| The end user must add lines of code to their app to enable it in HID Enterprise. |

In most cases, you can make the antecedent plural to keep agreement with the pronoun.

| **Correct** |
|---|
| End users must add lines of code to their app to enable it in HID Enterprise. |

In many cases, and preferably, you can rewrite the sentence to be more direct.

| **Correct and better** |
|---|
| You must add code to your app to enable it in HID Enterprise. |

The following examples are not acceptable uses of pronouns in HID documentation:

| **Issue** | **Example** |
|---|---|
| Noninclusive | The end user must add lines of code to his or her app to enable it in HID Enterprise. |
| Sexist | The end user must add lines of code to her app to enable it in HID Enterprise. |
| Sexist | The end user must add lines of code to his app to enable it in HID Enterprise. |

If you refer to an actual person in your writing, ask for their pronouns and use those. Don't assume or guess.

#### Personal pronouns
Use the second-person pronoun, "you", in HID documentation. Avoid first-person pronouns, such as "I", "our", "us", and "we", unless you are responding to customer feedback or are writing a tutorial.

#### Relative pronouns

"That", "which", and "who" are relative pronouns and don't all mean the same thing.

##### That

"That" introduces an essential clause. If you remove the words after "that", the sentence doesn't make sense.

| **Correct** |
|---|
| For HDFS working directory, provide the path in HDFS **that** you want Hunk to use as a working directory. |

##### Which

"Which" introduces a nonessential clause. If you remove the words after "which", the sentence still makes sense, although it is less detailed.

| **Correct** |
|---|
| HID Enterprise changes one of the default port settings in the server.conf file, **which** is one of the stanzas you copied but didn't edit. |

##### Who

When referring to a person, use "who" instead of "that".

#### Vague pronouns

Avoid ambiguous references between a pronoun and its antecedent. Vague pronouns include "this", "that", "which", and "it". To add clarity, replace the vague pronoun with a noun.

| **Correct** | **Incorrect** |
|---|---|
| Set the enableReduction value to true. | Set it to true. |

### Recommendations

Readers come to HID documentation looking for the best way to use their product to achieve a goal. To accommodate this use, treat all documentation as a recommendation. Don't make specific recommendations, but instead guide the reader to the best choice using concrete language and direct instructions.

#### Best practices

When you want to state a preference or a recommendation, apply the following guidelines in the documentation:

- Offer users encouragement, best practices, and the optimal way to use their product for their specific scenario.
- Don't use phrases like "It is recommended to", "HID recommends", or "We recommend". Instead, rephrase recommendations as requirements or best practices.
- Explain the reason why something is recommended instead of stating that it's recommended.
- Use callout boxes to bring attention to important information that a user needs to be aware of, such as how to avoid data loss, but don't document worst-case scenarios or situations a user can avoid.
- Include prerequisites, requirements, and decision support when necessary.
- If there are multiple ways to do something, phrase the recommended way as an imperative statement and place that method before the other options.

#### Examples

Writing factual, direct statements helps a user understand why an option is a good idea and whether it applies to them. See the following examples:

| **Correct** | **Incorrect** |
|---|---|
| To minimize system impact, perform this action outside of normal business hours. | It is recommended to perform this action outside of normal business hours. |
| Concealing specific values in spans is the best way to hide sensitive information in spans. | We recommend concealing specific values in spans. |
| Take the time to learn which indexes contain your data, the sources of your data, and the source type of that data. Knowing this information helps you narrow your search results. | HID recommends that you take the time to learn which indexes contain your data, the sources of your data, and the source type of that data. |
