# Type: InputRichBlockPullQuotation

**Category**: Rich messages

**Description**: A quotation with centered text, loosely corresponding to the HTML tag <aside>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockpullquotation)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "pullquote" |
| text | RichText | Yes | Text of the block |
| credit | RichText | Optional | Optional. Credit of the block |
