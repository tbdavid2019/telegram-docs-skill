# Type: InputRichBlockDetails

**Category**: Rich messages

**Description**: An expandable block for details disclosure, corresponding to the HTML tag <details>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockdetails)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "details" |
| summary | RichText | Yes | Always shown summary of the block |
| blocks | Array of InputRichBlock | Yes | Content of the block |
| is_open | Boolean | Optional | Optional. Pass True if the content of the block is visible by default |
