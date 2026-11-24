# Type: RichBlockExpandableBlockQuotation

**Category**: Rich messages

**Description**: A block quotation, corresponding to the HTML tag <blockquote> with the custom attribute "expandable".

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockexpandableblockquotation)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "expandable_blockquote" |
| blocks | Array of RichBlock | Yes | Content of the block |
| credit | RichText | Optional | Optional. Credit of the block |
