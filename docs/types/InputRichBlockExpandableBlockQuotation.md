# Type: InputRichBlockExpandableBlockQuotation

**Category**: Rich messages

**Description**: A block quotation, corresponding to the HTML tag <blockquote> with custom attribute "expandable".

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockexpandableblockquotation)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "expandable_blockquote" |
| text | RichText | Yes | Content of the block |
| credit | RichText | Optional | Optional. Credit of the block |
