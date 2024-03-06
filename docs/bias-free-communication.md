# Bias-free communication

## Write unbiased documentation

HID documentation serves a global audience, so it's essential that the documentation reflects the full scope of the HID community. Know that words have meanings beyond their dictionary definitions, and strive to write unbiased documentation that considers the experiences of everyone.

When writing about HID products, keep inclusivity in mind and follow these guidelines:

| **Guideline** | **Additional information** |
|---|---|
| Write in plain language. Metaphors and idioms aren't always understood internationally and can be offensive to some cultures. | [Use plain language](voice-and-tone.md#use-plain-language) |
| Use gender-fair wording and neutral pronouns in your writing. | [Gender-neutral pronouns](grammar-and-word-choice.md#pronouns) |
| Choose diverse names and genders when you create scenarios and examples. | [Names](grammar-and-word-choice.md#names) |
| Make sure your writing meets accessibility standards and requirements. | [Write accessible documentation](accessibility.md#write-accessible-documentation) |
| Avoid biased words, terminology, and language in your writing. | [Alternatives to biased language](#alternatives-to-biased-language) |

## Determining whether a term shows bias

When writing HID docs, be aware of your own biases in your writing. A term that isn't offensive to you might be problematic for someone else. To determine whether a term shows unconscious bias or harms a marginalized or underrepresented group, consider the following points:

- Don't use words that diminish the historical or current situations of others. For example, use "peer" instead of "slave".
- Don't use words that place a positive or negative connotation on color, race, or people. For example, write "deny list" instead of "blacklist".
- Don't use words that imply otherness or that exclude a group. For example, use "everyone" instead of "mankind".
- Don't use words that harm, degrade, or insult anyone or any group, whether it be mental, physical, sexual, functional, or criminal. For example, use "placeholder data" instead of "dummy data".
- Don't use words that imply elitism or a position of power. For example, write "primary" instead of "master".
There's a lot of nuance and complexity in the evolving English language, so if a word doesn't fit one of these examples and it makes you uncomfortable, don't use it. If someone tells you that a word makes them uncomfortable, take their opinion as an opportunity to learn. Research the term and discuss its usage with an editor. Everyone deserves documentation that speaks to them rather than against them.

## Alternatives to biased language

The following table provides examples of biased language along with suggested alternatives. The examples in the table aren't exhaustive, but instead are meant to act as a starting point to help you consider how to use inclusive language in your writing. You can also look for other terminology replacements in the Usage dictionary.

| **Biased word or phrase** | **Use this language instead** | **Type of bias** |
|---|---|---|
| Abnormal | Atypical, not typical | Ableist, disparaging |
| Blacklist | Deny, deny list, reject, exclude | Color bias, racist |
| Disable, disabled, disables | Deactivate, deactivated, deactivates, deselect, deselected, deselects, hide, hidden, hides, inactive, turn off, turned off, turns off, unavailable, makes unavailable | Divisive, disparaging |
| First-class entity | Top-level entity | Divisive |
| Flesh-colored, skin-toned | Dark brown, cream, beige | Color bias |
| Grandfathered | Exempt | Gendered language, racist |
| He, him, his, she, her, hers | You, your, they, their, them, a user, the users | Gendered language, sexist |
| Illegal characters | Invalid characters | Disparaging |
| Mankind | All, everyone, humanity, humankind | Gendered language, sexist |
| Master | Manager, primary | Divisive, racist |
| Master branch | Main branch | Divisive, racist |
| Sanity check | Review, verification | Disparaging |
| Slave | Peer, secondary, replica | Divisive, racist |
| Whitelist | Allow list, allow, accept, include | Color bias, racist |

### What about other words?

You might have questions about other types of words, such as violent language, potentially distressing terminology, or phrases that mention a color. Those terms are not inherently biased and aren't listed in the preceding section, but you are always welcome to write with more thoughtful language.

### Documenting biased language in the product

Teams at HID are working to remove biased language in HID products. As a writer, you might see biased terms in the HID product code or in third-party products that you can't change or ignore. In these cases, use unbiased language wherever you can to stop perpetuating the use of a biased term.

HID documentation matches the product. If your situation aligns with any of the following examples, match the exact name from the product for clarity:

- A field in HID software
- A setting in a .conf file
- A UI element
- Any other part of a HID product
- An outside source or system

In all other cases, such as when describing a functionality or a general concept rather than a specific part of the product, use unbiased language instead. See [Alternatives to biased language](#alternatives-to-biased-language) for examples.

## Use device-agnostic language

Customers interact with HID software using many kinds of devices and input methods, such as mobile devices and voice commands. Unless you know that customers use a product only on a certain device, assume that HID software works across a range of devices. Device-specific words like "click" and "type" aren't inclusive to all users and the ways they interact with the software.

To write for HID customers who use a variety of devices, including keyboards, mice, mobile devices, speech-to-text software, screen readers, and other assistive and adaptive technologies, use device- and input-agnostic language in your docs.

### Focus on the action, not on the gesture

Device-specific language like "double-click" and "right-click" doesn't consider users who use keyboards and mobile devices. Words like "press" and "tap" don't consider users who interact with touch screens through voice commands.

If you're tempted to use a device-specific gesture when the user has the option to use a number of devices, think of an inclusive term that focuses on the action a user performs instead of the motion they take on a device.

"Enter" and "select" work well for most situations and devices.

#### Enter

Use "enter" when referring to the inputting of text. See the following examples:

| **Correct** | **Incorrect** |
|---|---|
|For the **Destination** field, enter **ca_counties**. | For the **Destination** field, type c**a_counties**. |
| Enter your password. | Type your password. |
| Enter your search in the search bar. | Type your search in the search bar. |

#### Select

Use "select" when referring to highlighting text, clicking a link, choosing menu items, clicking a button or tab, pressing keys on a keyboard, or interacting with a touch-based user interface. See the following examples:

| **Correct** | **Incorrect** |
|---|---|
| Select the text that you want to copy. | Right-click the text that you want to copy. |
| Select the link. | Click the link. |
| Select the container folder to open it. | Double-click the container folder to open it. |
| Select a time period from the drop-down menu. | Choose a time period from the drop-down menu. |
| Select **Modify**. | Click **Modify**. |
| Select the **Patterns** tab. | Click the **Patterns** tab. |
| Select **Esc**. | Press **Esc**. |
| Select a dashboard to view it. | Tap a dashboard to view it. |

### What if "enter" and "select" don't work?

As much as possible, avoid language that's specific to any single device or input option. You can use other device-agnostic terminology if those verbs fit the situation better. Here are some examples:

- Check
- Navigate to
- Open
- Remove
- Toggle
- Uncheck
- Undo
- Zoom in

If you know that customers must perform an action in a specific way on a particular device, it's acceptable to use device-specific language to describe how they perform that function. For example, you might describe the physical interaction needed to scan a 3D object in HID AR for iOS on an iPhone or iPad.

To find mobile terminology and other terminology replacements, see the [Usage dictionary](usage-dictionary.md).
