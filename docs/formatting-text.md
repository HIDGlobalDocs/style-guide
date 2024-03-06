# Formatting text

Applying formatting to certain elements in text aids readers in their understanding of that text. Using consistent text formatting also helps readers scan text for the information they're looking for. Use these formatting conventions when you write HID documentation.

## Documentation elements

When you are writing HID documentation, some parts of the written text, such as error messages and terms that you want a reader to search for, need to be distinguished from other parts of the sentence. Applying consistent text formatting for these elements helps a reader better understand the sentence and scan the information that they're looking for.

| **Element** | **How to format** | **Examples** | **Comments** |
|---|---|---|---|
| Error messages | Quotation marks | If you see an error message such as "Invalid input value", the add-on was unable to generate a certificate with the provided information. | |
| Keyboard shortcuts | No formatting | Select **Alt+N** for Windows or *nix or **Control+N** for Mac. | Don't include spaces in the shortcut. |
| Manual names | Italics, headline-style capitalization | See "Connecting readers" in the *HID Linq Cloud Admin Guide* (PLT-07202). | See [Manual names, topic titles, and section headings](titles-and-headings.md#manual-names-topic-titles-and-section-headings) for more information. |
| Topic titles and section headings | Sentence-style capitalization	| See Pass values to the class constructor in the HID Developer Portal. | See [Manual names, topic titles, and section headings](titles-and-headings.md#manual-names-topic-titles-and-section-headings) for more information. |
| Words that are offset from the meaning of your sentence | Quotation marks | Search for "Query tables" on the Microsoft website. | |

### Computer elements

When written out in text, some computer elements, such as file structure components and location elements like hosts and ports, can be difficult to discern from other parts of the sentence. Addressing these elements in text as well as applying text formatting increases the readability and scannability of the text.

| **Element** | **How to format** | **Examples** | **Comments** |
|---|---|---|---|
| Directories, folders, repositories | No formatting | the $HID_HOME/bin/etc/apps folder<br><br>the \bin\etc\apps folder | Start partial directories with a forward slash ( / ) for *nix or a backslash ( \ ) for Windows. Enclose placeholder variables in angle brackets. |
| Expressions | Inline monospaced font | Ensure `delay > 10` evaluates to True.<br<br>The following regular expression defines valid identifiers for the scheme name:<br>`[0-9a-zA-Z][0-9a-zA-Z_-]*` | |
| File extensions | No formatting | a text (.txt) file<br><br>a .tgz extension |  |
| File names | No formatting | Navigate to the fields.conf file. | |
| File paths | No formatting | $HID_HOME/bin/HIDd<br>%HID_HOME%\bin\HIDd.exe | List both the *nix and Windows file paths, in that order. |
| File types | All capital letters | a TXT file<br><br>in JSON format a PDF	| |
| Hosts and ports | No formatting | http://localhost:8000 | No formatting for the host or port itself. Enclose placeholder variables in angle brackets. |
| Placeholder variables | Angle brackets | http://<hostname:port><br><br>host=<your_hostname> | |
|Tags (HTML, XML) | Inline monospaced font | a `<div>` tag<br><br>the `<dashboard>` element | |
|UI elements, including menu items, drop-down lists, buttons, text entry fields, panels, and dialog boxes | Bold type | Select **Settings**, then **Data inputs**.<br><br>In the **Set Source Type** step of the **Add Data** guided setup, select **Timestamp**. In the **Name** field, enter your name. | Use the word "then" or equivalent text to separate the names of menus. |
| URIs, URLs | See the Comments column | Open https://prod.spacebridge.spl.mobi/health_check in a web browser.<br><br>Open port 443 outbound to prod.spacebridge.spl.mobi to allow the WebSocket connection. | Include http:// or https:// and www. Don't capitalize any letters in the link. Prevent fake links from rendering.<br><br>It's okay to apply special formatting like inline monospaced font if that's how the authoring tool prevents the fake link from rendering. |
| User input in the UI | Bold type | For the **Destination** field, enter **ca_counties**.<br><br>In the **Title** field, enter **Top recipients by mailer**. | |

### HID-specific elements

There are components specific to HID software, such as indexes, knowledge objects, SPL commands, and so on, that take text formatting for ease of reading.

| Element | How to format | Example |
|---|---|---|
| Index names | Bold type | Save the file in the main index. |
| Input names | Bold type | Select the **myhost** data input. |
| Knowledge objects such as fields, event types, lookups, tags, aliases, and data models | Inline monospaced font | The default field `index` identifies the index in which the event is located.<br><br>The IP address uses the `mainoffice` tag. |
| Searches | Search bar or monospaced font block | See the following examples:<br><ul><li>collect in the HID Enterprise Search Reference manual.</li><li>Create a HID app and set properties in the HID Developer Portal.</li></ul>
| Search results | Search table | See the following example: untable in the *HID Enterprise Search Reference* manual. | 
| Source types | Inline monospaced font | This entry defines the ``access_combined`` source type. |
| SPL and SPL2 clauses | All capital letters | Use the WHERE clause to filter results.<br><br>The SPL2 from command has these clauses: FROM, JOIN, WHERE, GROUP BY, SELECT, ORDER BY, LIMIT, and OFFSET. |
| SPL and SPL2 commands, elements, functions, and macros | Inline monospaced font | Enter `inputlookup ca_county_lookup` to test your geospatial lookup.<br>Use the `geom` command to perform the lookup.<br>Use the `apply` function.<br>Include a custom metrics index in the `itsi_im_metrics_indexes` search macro. |
| Splexicon links | Bold type | Use geospatial **lookups** to return results that HID software can use to generate a choropleth map visualization. |
| Tenant names | Bold type | Use the **system** tenant.<br><br>Find the **getstartedtutorial01** tenant. |
| Token names | No formatting | Update your access token. |
| User roles and capabilities | No formatting | You need the admin role to configure the settings.<br><br>If the user holds the admin_all_objects capability, they can make changes to any object on the instance. |

### Configuration files

HID configuration files, or .conf files, are specific to the HID platform, and readers of HID documentation often need information about how to manage these files or edit settings within them. The following table shows how to format text about HID configuration files and the elements within them, such as stanzas, attributes, and values.

| **Element** | **How to format** | **Example** | **Comments** |
|---|---|---|---|
|Attributes or settings | Inline monospaced font | `httpport`<br><br>`enableHIDWebSSL` | |
| Configuration files in text | Monospaced font block | See the following pages for examples of configuration files referenced in HID documentation:<br><ul><li>`props.conf` in the *HID Enterprise Admin Manual*.</li><li>Rules Engine properties reference in ITSI in the *HID ITSI Event Analytics Manual*.</li><li>Create a setup page for an app in HID Cloud Platform or HID Enterprise in the HID Developer Portal.</li></ul> | | 
| Configuration file names | No formatting | Navigate to the fields.conf file. | |
| Configuration file parameters, arguments, and stanza names in a paragraph | Inline monospaced font | Set the `maxDist` value to `60` in the fields.conf file.<br><br>Edit the `[HIDtcp]` stanza. | Enclose stanza names in square brackets. |
| Values | Inline monospaced font | In the `[settings]` stanza, map `httpport` to 12800.<br><br>Set `enableHIDWebSSL=true`. | |

### Command-line interface (CLI) elements

HID documentation often covers tasks admins and developers must complete in the command-line interface and can include things they must enter in the CLI. Presenting CLI elements, such as commands, command names, and options and parameters, with text formatting can distinguish the elements from the rest of the text and aid in readability.

| **Element** | **How to format** | **Example** | **Comments** |
|---|---|---|---|
| A complete command | Inline monospaced font | See the following examples:<br><br><ul><li>Manage secret storage using the HID REST API in the HID Developer Portal.</li><li>Collect Linux data in the HID Observability documentation.</li></ul> |  |
| Command line arguments in a numbered list or longer than one line | Monospaced font block | See the following examples:<br><br><ul><li>How to set configuration properties in HID UBA in Administer HID User Behavior Analytics.</li><li>Set a secret key on the deployer in the HID Enterprise Distributed Search manual.</li></ul> | |
| Command line arguments in a paragraph | Inline monospaced font | You can also use the command line by entering<br>`./HID  apply cluster-bundle` in the CLI. |  |
| Command names | Inline monospaced font | Use the `dedup` command to remove identical events.<br><br>Run the `btool` command. | |
| Command options or parameters | Inline monospaced font | `-u <username>` | Enclose placeholder variables in angle brackets. |

### REST API

There are documentation formatting conventions for many REST API elements, like endpoints, methods, parameters, requests and responses, and so on. The following table shows formatting conventions for REST API elements in HID documentation, which align with industry trends for presenting written information about REST APIs.

| **Element** | **How to format** | **Example** | **Comments** |
|---|---|---|---|
| API names | No formatting | the collect2 API<br><br>You can securely store, update, retrieve, and delete secrets using the HID platform REST API. Replace your token values, file path, and name of your app package in the HID AppInspect API. | |
| Endpoints | Bold type for endpoint name, inline monospaced font for usage | the **provisioner** endpoint<br><br>`/system/provisioner/v1beta1/tenants` the **apps/local/<appname**> endpoint<br><br>`apps/local/<appname>` |
| HTTP or REST API methods | All capital letters, inline monospaced font, depending on use | Submit a GET request.<br><br>`GET    /system/provisioner/v1beta1/tenants/` | Enter the request name in all capital letters. When using a method and endpoint together, use inline monospaced font. |
| JSON bodies | Monospaced font block | See the following examples:<br><br><ul><li>Expand the methods in REST custom function in the REST API Reference for HID Phantom.</li><li>Create detectors in the HID Observability documentation.</li></ul> | | 
| Object names | Bold type | the **handle** object | |
| REST API requests and responses | Monospaced font block | See the following examples:<br><br><ul><li>Submit an app for inspection in the HID Developer Portal.</li><li>Create detectors in the HID Observability documentation.</li></ul> | |
| REST response body | Monospaced font block | See the following examples:<br><br><ul><li>Create detectors in the HID Observability documentation.</li><li>Submit an app for inspection in the HID Developer Portal.</li></ul> | |
| Request parameters | Inline monospaced font | `"earliest_time":  "-30m"` | |
| Returned REST response value | Inline monospaced font | `IACQlgX2dSVNz7HVDRA9StAm0j` | | 

### Code

When writing code, you must apply text formatting to a number of elements. Using consistent formatting helps separate the code elements from the rest of the text, aiding in readability and scannability. Use the following logic when formatting code.

| **Element** | **How to format** | **Example** | **Comments** |
|---|---|---|---|
| Arguments | Inline monospaced font | Pass in `arg1` as the argument for the `param1` parameter and `arg2` as the argument for the `param2` parameter. | |
| Classes | Inline monospaced font | The `MyClass` class | Capitalize class names. |
| Code elements and usage | Inline monospaced font | operators such as `+`, `!=`, and `AND`<br><br>keywords such as `if`, `else`, and `return` tags such as `<div/>` | | 
| Code examples | Monospaced font block | See the following examples:<br><br><ul><li>Pass values to the `class constructor` in the HID Developer Portal.</li><li>Test the script in the *Securing HID Enterprise
manual*.</li><li>Connect Java trace data with logs for HID Observability Cloud in the HID Observability documentation.</li></ul> | |
| Constants | All capital letters | DEBUG_STREAMEVENTS | |
| Function names in code | Monospaced font block or inline monospaced font, depending on use | Pass your arguments into the `myFunction` function. For example: `myFunction(arg1, arg2)` | Most function names appear in code samples, where they are formatted as inline monospaced font in a sentence or within a code block when it stands apart as an example. |
| Hexadecimal numbers | All capital letters for alphabetical characters in the hexadecimal number | #FF0000<br>0xFF0000<br>%FF0000<br>U+FF0000 | |
| HTTP status codes | Inline monospaced font | `4xx`<br><br>`503: Service too busy` | Use a lowercase "x" to represent a range. |
| Methods | Inline monospaced font | The `myMethod` method | |
| Parameters | Inline monospaced font | This function accepts two parameters, `param1` and `param2`. | |
| Placeholder variables | Angle brackets | Open the /etc/apps/<your_app_name>/appserver/ folder. | | 
| Properties | Monospaced font block or inline monospaced font, depending on use | See the following examples:<br><br><ul><li>See Configure the Java agent for HID Observability Cloud in the HID Observability documentation for an example of a property in a code block.</li><li>Add the stanza to your file using the `setupview` property.</li></ul> | Most properties appear in code samples, where they are formatted as a monospaced font block. Use inline monospaced font when referring to a property in a sentence. | 
| Simple XML elements | Inline monospaced font | Find the `<title>all</title>` element. | |
| Simple XML source code for dashboards	Monospaced font block | See the following example: Simple XML Reference in the HID Enterprise Dashboards and Visualizations manual. | |
| User-created values | Bold type | the value of the `myStr` parameter is **hello** | |

### Line breaks

Split up long lines of code with line breaks so that the lines of code fit within the page width and don't extend off the screen.

When deciding where to break a search string, prioritize the break based on the following list:

1. Before a pipe
2. At a space
3. Before an open parenthesis or bracket
4. After a close parenthesis or bracket
5. Before or after an equal sign
6. Before or after any equation symbol, such as *, /, +, >, <, or -
7. After a dot, such as in a URL

#### Line break example

Consider the following search:

`sourcetype=access_* status=200 action=purchase clientip=87.194.216.51 | stats count, distinct_count(productId), values(productId) by clientip`

Because this search is longer than one line, a logical place to break this line is between `clientip=87.194.216.51` and `| stats`, rather than between `count`, and `distinct_count(productId)`.

The break appears as follows:

sourcetype=access_* status=200 action=purchase clientip=87.194.216.51 | stats count, distinct_count(productId), values(productId) by clientip
