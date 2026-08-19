# Type: InputRichBlockSlideshow

**Category**: Rich messages

**Description**: A slideshow, corresponding to the custom HTML tag <tg-slideshow>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockslideshow)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "slideshow" |
| blocks | Array of InputRichBlock | Yes | Elements of the slideshow |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
