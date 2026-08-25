# Type: InputRichBlockDocument

**Category**: Rich messages

**Description**: A block with a general file, corresponding to the custom HTML tag <tg-document>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockdocument)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "document" |
| document | InputMediaDocument | Yes | The document. Caption is ignored. |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
