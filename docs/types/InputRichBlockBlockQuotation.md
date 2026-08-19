# Type: InputRichBlockBlockQuotation

**Category**: Rich messages

**Description**: A block quotation, corresponding to the HTML tag <blockquote>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockblockquotation)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "blockquote" |
| blocks | Array of InputRichBlock | Yes | Content of the block |
| credit | RichText | Optional | Optional. Credit of the block |
