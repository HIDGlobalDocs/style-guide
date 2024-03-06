# Tables

## Best practices for including tables

A table is a good way to present descriptions of choices, options, and fields that a user might encounter in a task. You can also use tables for reference information, decision support, compatibility matrices, and choices a user has.

Keep tables as simple as possible, and make sure that screen readers can easily parse tables. For more information about making tables accessible in HID docs, see [Write accessible documentation](accessibility.md#write-accessible-documentation).

Here are some best practices for creating effective tables.

### Do

- Introduce tables with a full sentence and a colon.
- Always include a header row and include text in all header row cells.
- Capitalize the first letter of every cell entry.
- Use parallel sentence construction in cell entries that belong to the same column. For example, start all entries with verbs, or end all entries with punctuation.
    - If the cell contents are complete sentences, include end punctuation.
    - If the cell contents are characters, words, or phrases, don't include end punctuation.
- Use code samples sparingly in tables.
- You can use tables in a list of task steps.

### Don't

- Don't create a table with only one row.
- Don't use X or another character to indicate compatibility or support. Instead, use Yes and No. See [Spell out words and symbols](accessibility.md#spell-out-words-and-symbols) for more information.
- Avoid using lists inside table cells.
- Avoid merging or splitting table cells.
- Avoid leaving table cells empty. If you need to keep a cell blank, use a nonbreaking space to make a cell appear blank. The HTML character entity for a nonbreaking space is `&nbsp;`.
- Avoid including links in tables, unless the purpose of the table is to help users find information in the docs.
