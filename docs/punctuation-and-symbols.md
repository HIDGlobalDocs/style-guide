# Punctuation and symbols

## Show symbols in text

You can show a symbol in your text when you must describe the exact user input, such as with code syntax.

Don't use symbols to substitute for a meaning that is not listed in the What to call symbols section. Consider whether you can spell out the meaning of the symbol using words instead. See [Spell out words and symbols](accessibility.md#spell-out-words-and-symbols) for more information.

If you want to show a symbol in your text, write out the symbol first, and then refer to the symbol in parentheses with nonbreaking spaces. The HTML character entity for a nonbreaking space is `&nbsp;`.

| **Correct** | **Incorrect** |
|---|---|
| Begin the line with a forward slash ( / ).<br>Enter your search after the pipe ( \| ). | Begin the line with a forward slash, /.<br>Enter your search after the \|. |

### What to call symbols

Use the following terms when writing about symbols in HID documentation:

| **Symbol** | **What to call it** |
|---|---|
| ` | Backtick |
| ~ | Tilde |
| ! | Exclamation point |
| @ | At symbol |
| # | Pound sign (or hash symbol?) |
| $ | Dollar sign |
| % | Percent sign |
| ^ |Caret |
| & | Ampersand |
| * | Asterisk, wildcard |
| ( | Left parenthesis |
| ) | Right parenthesis |
| - | Dash, hyphen, minus sign |
| - | Underscore |
| = | Equal sign |
| + | Plus sign |
| [ | Left bracket |
| ] | Right bracket |
| { | Left brace, left curly brace |
| } | Right brace, right curly brace |
| \ | Backslash |
| \| | Pipe, vertical bar |
| ; | Semicolon |
| : | Colon |
| ' | Single quotation mark |
| " | Double quotation mark |
| , | Comma |
| < | Less than, left-pointing angle bracket |
| . | Period, dot, or point depending on context. See [Period](#period). |
| > | Greater than, right-pointing angle bracket |
| / | Forward slash |
| ? | Question mark |

## Ampersand

Don't use an ampersand in place of the word "and". Always write out "and" unless the ampersand is part of a proper name. See the following example:

- Search & Reporting app

## Apostrophe

Use an apostrophe when writing contractions and making names possessive. Don't use an apostrophe to make product names, company names, or trademarked terms possessive or plural.

### When to use an apostrophe

You can use an apostrophe to write a contraction:

- Let's
- Don't
- Can't

You can use an apostrophe for possessive nouns that are not product names, company names, or trademarked terms:

- The user's credentials
- The organization's users
- The app's home page

### When not to use an apostrophe

Don't use an apostrophe to make a product name, company name, or trademarked term possessive. The following table lists incorrect and correct examples:

| **Incorrect** | **Correct** |
|---|---|
| The dashboard shows data pulled from HID Enterprise's internal log files. | The dashboard shows data pulled from the HID Enterprise internal log files. |
| Submit a case using HID's Support Portal. | Submit a case using the HID Support Portal. |
| Search's capabilities are robust. | The search function has robust capabilities. |

## Brackets

There are three kinds of brackets: angle brackets, curly braces, and square brackets.

### Angle brackets ( < and > )

Use angle brackets as a placeholder for variables you want the user to enter.

| **Correct** | **Incorrect** |
|---|---|
| Enter your user-specified domain in this format: `https://<user-specified domain>.HIDcloud.com`. | Enter your user-specified domain in this format: `https://{user-specified domain}.HIDcloud.com`.<br>Enter your user-specified domain in this format: `https://(user-specified domain).HIDcloud.com<`br>Enter your user-specified domain in this format: `https://[user-specified domain].HIDcloud.com` |

Do not use the right-pointing angle bracket ( > ) to indicate navigation through a series of menu item selections. Instead, spell out the sentence using a word like "then".

| **Correct** | **Incorrect** |
|---|---|
 | 1. Select **Start**, then **Administrative Tools**, then **Computer Management**. | 1. Select **Start** > **Administrative Tools** > **Computer Management**. |

In order for an action to qualify as a step in a menu path, the action must be accessible within that menu. If completing a step in the path takes the user to a new page or menu where they complete another action, describe that action in a new task step instead of combining it in the same step.

| **Correct** | **Incorrect** |
|---|---|
| 1. In HID Web, select **Settings**, then **Advanced Search**.<br>2. On the **Advanced Search** page, select **Search commands**. | 1.	In HID Web, select **Settings** > **Advanced Search** > **Search commands**. |

### Curly braces ( { and } )

Use curly braces only when they are part of a code sample or other string literal.

### Square brackets ( [ and ] )

Use square brackets around a .conf file stanza name or within code.

| **Correct** | **Incorrect** |
|---|---|
| Edit the `[HIDtcp]` stanza.<br>Specify a subsearch that starts with this search command: `tag=dns query [search tag=malware]`. | Enter your user-specified domain in this format: `https://[user-specified domain].HIDcloud.com`. |

## Colon

These are the ways to use a colon properly in your writing:

| **Scenario** | **Example** |
|---|---|
| To introduce unordered lists, tables, or images. Always precede lists, tables, and images with a full sentence. | Use a full sentence and a colon to introduce the following items:<ul><li>Unordered lists</li><li>Tables</li><li>Images</li></ul> |
| To introduce a list within a sentence. | The application can access the following items: the file system, the command line, and other applications. |

## Comma

Although there are many rules for when to use a comma, these are the most common in HID documentation:

| **Scenario** | **Example** |
|---|---|
| To separate a list of 3 or more words or word groups. This type of comma is known as the serial, or Oxford, comma. | Generate reports, views, and dashboards.<br>I'd like to thank my parents, Mother Teresa, and the pope. |
| To separate adjectives when they each modify the noun independently. | The feature groups the extracted fields into a single, ordered sequence. |
| To offset appositives from the rest of the sentence. | Use wiki markup when you don't have any elements, such as code or a table, following a step. |
| After a prepositional phrase.| After reviewing the document, I had a chance to compile a list of reading material. |

Don't use commas to separate two-verb phrases that modify the same subject.

| **Correct** | **Incorrect** |
|---|---|
| I collected the various pieces of documentation and forwarded them to the appropriate parties. | I collected the various pieces of documentation, and forwarded them to the appropriate parties. |

## Dashes

Don't use dashes to list items. Use a bulleted list.

### Hyphen (-)

Use a hyphen for compound adjectives that precede the noun they modify, and don't use a hyphen if the adjectives follow the noun they modify. Don't add spaces before or after the hyphen.

| **Correct** | **Incorrect** |
|---|---|
| a case-sensitive username<br>the password is case sensitive | a case sensitive username<br>the password is case-sensitive |

### Em dash ( — )

Don't use em dashes in HID documentation. Keep your sentences short, and use two sentences or commas to separate breaks in thought.

### En dash ( – )

Don't use en dashes in HID documentation.

## Exclamation points

It's okay to use exclamation points in programming and scripting languages, .conf files, and Search Processing Language (SPL) searches, but do not use exclamation points as terminal punctuation in HID documentation or UI text.

Exclamatory statements are better suited for blog posts and marketing materials. See the following examples:

| **Correct** | **Incorrect** |
|---|---|
| <ul><li>When you want to exclude results from your search, you can use the NOT operator or the `!=` field expression.</li><li>You can specify dimensions, properties, or tags that you want to exclude from the results. Enter an exclamation point ( ! ) in the filter field to represent a Boolean NOT operator.</li></ul> |
| <ul><li>Learn more about Search Processing Language (SPL) here!</li><li>Return to the home page!</li><li>The HID Distribution of OpenTelemetry Ruby is a beta feature subject to future changes!</li></ul> |

## Parentheses

Make the point in each of your sentences without using parentheses. Don't use parentheses in place of commas, to enclose a complete sentence, or to include unnecessary information or an afterthought.

!!! note

    Don't write a lowercase "s" or "es" in parentheses, "(s)" or "(es)", after a noun to indicate both singular and plural. Choose the best option for your documentation.

You can use parentheses in the following cases:

- To introduce an abbreviation
- To enclose a symbol
- For optional steps in a task
- In SPL commands and functions

### Abbreviations

You can use parentheses to introduce an abbreviation.

| **Correct** | **Incorrect** |
|---|---|
| Use the HID Search Processing Language (SPL) to search your data. | Use SPL (the HID Search Processing Language) to search your data. |

### Symbols

Use parentheses to enclose a symbol after spelling it out.

| **Correct** | **Incorrect** |
|---|---|
| Begin the line with a forward slash ( / ). | Begin the line with a forward slash, /. |

### Optional steps in tasks

You can use parentheses when explaining that a step is optional in a task.

| **Correct** | **Incorrect** |
|---|---|
| (Optional) Provide the context for the task in a new paragraph. | Optional: Provide the context for the task in a new paragraph.<br>Provide the context for the task in a new paragraph (optional). |

### SPL commands and functions

You can also use parentheses when writing about one or more fields in statistical commands and charting functions for SPL. See the following example:

- Use with `earliest(x)` and `latest(x)` to calculate the rate of increase.

## Percent

Use a numeral plus the percent sign ( % ) to specify an exact percentage in text and tables. Don't use the word "percent".

| **Correct** | **Incorrect** |
|---|---|
| 10% | Ten percent<br>10 percent |

Use "percentage" as a noun when you're not specifying an exact quantity.

## Period

Use a period at the end of full sentences, and don't use a period at the end of sentence fragments or after the last item in an unordered list. Use only one space after a period, or any other punctuation, that ends a complete sentence.

Be aware of the differences in these terms, which are all represented by a period character:

| **Term** | **Usage** |
| dot | The character used in domain names, email addresses, and computer files. |
| full stop | This term is traditionally British English. Don't use in HID documentation. |
| period | The name for the punctuation mark used at the end of a sentence. |
| point | The dot glyph used in numbers to separate the fractional part from the integer part. |

## Quotation marks

There are differences between single quotation marks and double quotation marks, how to style them, and where to place punctuation that is used near a quotation mark.

### Use logical quotation

When you place a keyword or other string literal within quotation marks, put punctuation, like commas and periods, outside of the final quotation mark.

| **Correct** | **Incorrect** |
|---|---|
| If you see the message "Authentication Failed", try logging in again.<br>The message shows "Authentication Successful". |
| If you see the message "Authentication Failed," try logging in again.<br>The message shows "Authentication Successful." |

### Use straight quotation marks

Use straight quotation marks instead of curly quotation marks when you write. In certain scenarios, especially in code examples, you must use straight quotation marks because curly quotation marks cause code to break. A better practice is to use straight quotes everywhere in your writing.

### When to use single quotation marks

Use single quotation marks for code examples in languages that use the mark. See the following example:

`HID_HOME = os.environ['HID_HOME']<br><br> LOGGING_DEFAULT_CONFIG_FILE = os.path.join(HID_HOME, 'etc', 'log.cfg')`

### When to use double quotation marks

Use double quotation marks to format the following elements:

- To offset words that aren't part of the meaning of your sentence
- Error messages

Don't use quotation marks for emphasis, to show user input in a HID product UI, or to enclose the names of UI elements.

| **Correct** | **Incorrect** |
|---|---|
| Search for "Query tables" on the Microsoft website.<br>If you see an error message that says "The user isn't authenticated", check the user's permissions. | Enter "Filename" into the UI field.<br>From the "Field" menu, select Filename. |

For a full list of formatting rules for commonly documented elements, including the elements that take quotation marks, see [Formatting reference](formatting-text.md).

## Slashes

There are two kinds of slashes: the backslash and the forward slash.

### Backslash ( \ )

Backlashes are used in a couple of ways:

- Backslashes are used in code.
- Windows operating systems use backslashes in URL and URI paths. When writing instructions for Windows users and developers, always include the *nix path first, followed by the Windows path. See the following example:

| **\*nix** | **Windows** |
|---|---|
| $HID_HOME/bin/HIDd | %HID_HOME%\bin\HIDd.exe |

### Forward slash ( / )

A forward slash has multiple meanings:

- *nix operating systems use forward slashes as a path divider. When writing instructions for *nix users and developers, always include the *nix path first, follow by the Windows path. See the following example:

| **\*nix** | **Windows** |
|---|---|
| $HID_HOME/bin/HIDd | %HID_HOME%\bin\HIDd.exe |

- Forward slashes can mean "and", "divide by", "or", "per", or "with". In most cases, use the word you intend instead of a slash. You can use the forward slash when you write about read, write, and delete permissions.

| **Correct** | **Incorrect** |
|---|---|
| Linux or Windows.<br>All registration information is written to and stored in the database.<br>An 8 CPU, 16 GB memory machine can achieve 50 to 60 Mb per second throughput.<br>Add read/write permissions for all users. | Linux and/or Windows.<br>All registration information is written to/stored in the database.<br>An 8 CPU, 16 GB memory machine can achieve 50 to 60 Mb/second throughput. |
