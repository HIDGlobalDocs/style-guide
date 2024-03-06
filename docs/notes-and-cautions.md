# Notes and cautions

## Best practices for using callout boxes

Note and caution callout boxes allow you to highlight information on a page by surrounding text with a colored box. Note callout boxes provide important information that adds clarity to the content, and caution callout boxes provide critical information to the user before they make an irreversible decision.

### Before you include a callout box

Before you add multiple callout boxes to a topic, consider how the callouts look on the page. They might distract readers and affect the scannability of a topic.

If a callout box isn't essential to highlight your content, consider weaving that information into the introduction or as part of the instructions you're creating.

!!! note

    Use callout boxes judiciously. If the content of the note isn't relevant to your content, your reader might ignore future callout boxes.

### Guidelines for using callout boxes

Follow these guidelines when you use note and caution callout boxes:

- Avoid writing long notes and cautions.
- Don't confuse a note or caution with a prerequisite.
- Place notes and cautions after the text they pertain to. With steps in a task, however, make sure that the user doesn't need that information before they begin the task.
- Don't use a note or caution immediately after a topic title or section heading.
- Include links in notes or cautions only if the link helps the reader complete the task or is essential to their understanding of the content.
- Don't use other tags, styles, formatting, or words for notes and cautions inside the callout boxes. For example, don't use the term "Important" or "Tip" as a note label. The term "Warning" is used for danger and injury and is generally associated with hardware documentation.

For more guidance on when to use each type of callout box, see [Note callout boxes](#note-callout-boxes) and [Caution callout boxes](#caution-callout-boxes).

## Note callout boxes

Use a note callout box to provide an important piece of information or a tip that isn't an integral part of the content but that adds clarity or more information.

Use note callout boxes in the following situations:

- To supplement a point in the main text
- To supply information that applies in special cases
- To suggest alternative methods

Before using note callout boxes, see [Best practices for using callout boxes](#best-practices-for-using-callout-boxes).

### Example

See the following example of a note callout box:

!!! note

    If you have a HID Enterprise high-availability deployment, use per-result triggering carefully. If a peer is not available, a real-time search won't warn you that the search might be incomplete. To avoid this issue, use a scheduled alert instead.

## Caution callout boxes

Use a caution callout box to provide critical information that a user can't reverse if they continue with the task. Use caution callout boxes in the following situations:

- To warn a user of data loss
- To warn a user that an action can corrupt their data
- To let a user know that there's a consequence they can't reverse
- To tell a user to back up their data before they continue

Before using caution callout boxes, see [Best practices for using callout boxes](#best-practices-for-using-callout-boxes).

### Example

See the following example of a caution callout box:

!!! warning "Caution"

    Always use new instances. The process of adding an instance to a search head cluster overwrites any configurations or apps currently on the instance.