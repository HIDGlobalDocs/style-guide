# Lists

## Best practices for writing with lists

Lists organize important information so that readers can scan content faster. Use a list to organize multiple steps or items. Avoid writing tasks in paragraph form, unless the task contains only one step.

When you include lists in your content, consider these best practices:

- Introduce lists with a complete lead-in sentence that describes the purpose or the content of the list.
- Include more than 1 item in a list.
- Introduce only 1 idea, item, or action in each list item.
- Use no more than 2 levels in a list: a primary list and a sublist.
    - Use sublists sparingly to avoid overcomplicating information.
    - Ensure sublists have more than 1 item.
- Capitalize the first letter of every list item.
- In general, follow these punctuation guidelines for the items in a list:
    - If the list items are complete sentences, include end punctuation.
    - If the list items are characters, words, or phrases, don't include end punctuation.
- Use parallel sentence construction in list items. For example, start all list items with verbs, or end all list items with punctuation.
- In task steps, avoid linking to other topics within the task.
- Use lists in tables sparingly.

Use these best practices to make docs accessible for all audiences. For more guidance on making docs more accessible using lists, see [Write accessible documentation](accessibility.md#write-accessible-documentation).

### Choose the best list

Choose from the following lists based on your content:

| **Type of list** | **When to use** | **More information** |
|---|---|---|
| Bulleted list | When the list item order isn't important, such as a list of options. | See [Bulleted lists](#bulleted-lists). |
| Numbered list | When the order of the list items is important or the user is following sequential steps, such as a task. | See [Numbered lists](#numbered-lists). |
| Definition list | For a list of descriptions, definitions, associations, or explanations, such as a glossary or a set of terms. | See [Definition lists](#definition-lists). |

## Bulleted lists

When you write HID documentation, use a bulleted list (sometimes called an unordered list) when the order of list items isn't important. For example, you can use a bulleted list for a list of options.

### Qualities of bulleted lists

Bulleted lists must have the following qualities:

- A complete lead-in sentence that describes the list's purpose, punctuated by a colon
- A consistent hierarchy or order, such as alphabetization
- More than 1one list item
- No more than one sublist for each list item if needed, with at least two items in a sublist
- Parallel sentence construction
- Sentence case capitalization
- One sentence or idea for each list item
- End punctuation if the list items are complete sentences
- No end punctuation if the list items are characters, words, or phrases

For more guidance on using lists, see [Best practices for writing with lists](#best-practices-for-writing-with-lists).

### Example

The following example of a bulleted list contains a complete lead-in sentence. Each item in the list uses parallel construction and doesn't contain more than one phrase.

You can use the following types of Search Processing Language (SPL) commands:

- Eventing commands
- Generating commands
- Reporting commands
- Streaming commands

## Numbered lists

When you write HID documentation, use numbered lists, sometimes called ordered lists or task lists, when the order of the list items is important. For example, you can use numbered lists to organize procedural information or sequential steps a user must follow. If you add substeps, use an ordered list marked by lowercase letters. If you need to describe a set of options for a list item, use a bulleted list or a table.

### Qualities of numbered lists

Numbered lists must have the following qualities:

- A complete lead-in sentence that describes the list's purpose, punctuated by a period or a colon
- More than one list item
- No more than one sublist for each list item if needed, with at least two items in a sublist
- One action for each list item
- Parallel sentence construction
- Sentence case capitalization
- End punctuation if the list items are complete sentences
- No end punctuation if the list items are characters, words, or phrases

Avoid including links to other topics in task steps, unless in the case of a supertask, which is a numbered list composed of links to a series of tasks. See [Best practices for including links](links.md#best-practices-for-including-links). For more guidance on using lists, see [Best practices for writing with lists](#best-practices-for-writing-with-lists).

#### Formatting task steps

When you're writing task steps, follow these guidelines to accurately describe and format the step:

| **Type of task step** | **Guidance** | **Example** |
|---|---|---|
| Required step | Write in the imperative mood. | 1. Log in to your instance. |
| Conditional step | Phrase the step using an if statement. | 1. If you need to add an index to a single peer, create a separate indexes.conf file on the peer. |
| Optional step | Preface the step with the word "Optional" in parentheses. | 1. (Optional) Create a HID.com account. |

### Example

The following example of a numbered list contains a heading describing the task and a complete lead-in sentence. Each item in the list contains a single action and uses parallel construction. In step 3, the procedure has substeps marked by lowercase letters. In step 4, the example shows an optional step.

#### Search for sales of a specific product

Follow these steps to search for how many simulation style games were bought yesterday:

1. In the time range picker, change the time range to **Yesterday**.
2. Run the following search:<br>`sourcetype=access_* status=200 action=purchase categoryId=simulation`
3. Find the number of purchases for each type of product.
     1. Remove `categoryId=simulation` from your search criteria and run the search again.
     2. Locate the unique categoryId values by selecting the **categoryId field** in the **Selected Fields** list.
     3. Select a categoryId name. The categoryId is added to your search and the search is automatically run again. The results show the number of purchases for that product.
4. (Optional) For the number of purchases made each day of the previous week, run the search again for each time range.

## Definition lists

When you write HID documentation, use a definition list to define a set of terms, descriptions, explanations, or associations.

### Qualities of definition lists

Definition lists must have the following qualities:

- A complete lead-in sentence
- More than 1 defined term
- Two levels: the term, which is in bold and on its own line, and the definition, which is at least one full sentence indented on its own line
- Parallel sentence construction
- Sentence case capitalizationn
- One idea for each list
- End punctuation for every definition line

You can add a paragraph break after each definition if the formatting is tight. If you need to use multiple definition lists or organize more content, you might find that a table works better for this purpose. See [Best practices for including tables](tables.md#best-practices-for-including-tables).

For more guidance on using lists, see [Best practices for writing with lists](#best-practices-for-writing-with-lists).

### Example
The following example of a definition list contains a complete lead-in sentence. Each item in the list uses parallel construction and complete sentences.

You can run the following types of searches with the HID platform:

- Raw event search<br>
A raw event search retrieves events from an index and is typically used to analyze a problem, such as checking error codes, correlating events, investigating security issues, and analyzing failures.
- Transforming search<br>
A transforming search performs a statistical calculation against a set of results. For example, you can get a daily count of error events, count the login attempts from a user, or calculate the 95th percentile of field values.
