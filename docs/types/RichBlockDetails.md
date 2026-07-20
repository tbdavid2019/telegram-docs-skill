# Type: RichBlockDetails

**Category**: Rich messages

**Description**: An expandable block for details disclosure, corresponding to the HTML tag <details>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockdetails)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "details" |
| summary | RichText | Yes | Always shown summary of the block |
| blocks | Array of RichBlock | Yes | Content of the block |
| is_open | Boolean | Optional | Optional. True, if the content of the block is visible by default |
