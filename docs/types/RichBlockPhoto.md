# Type: RichBlockPhoto

**Category**: Rich messages

**Description**: A block with a photo, corresponding to the HTML tag <img>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockphoto)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "photo" |
| photo | Array of PhotoSize | Yes | Available sizes of the photo |
| has_spoiler | Boolean | Optional | Optional. True, if the media preview is covered by a spoiler animation |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
