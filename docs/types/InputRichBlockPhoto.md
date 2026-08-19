# Type: InputRichBlockPhoto

**Category**: Rich messages

**Description**: A block with a photo, corresponding to the HTML tag <img>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockphoto)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "photo" |
| photo | InputMediaPhoto | Yes | The photo. Caption is ignored. |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
