# Type: RichBlockDocument

**Category**: Rich messages

**Description**: A block with a general file, corresponding to the custom HTML tag <tg-document>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockdocument)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "document" |
| document | Document | Yes | The document |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
