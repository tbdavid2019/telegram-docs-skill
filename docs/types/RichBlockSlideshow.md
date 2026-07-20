# Type: RichBlockSlideshow

**Category**: Rich messages

**Description**: A slideshow, corresponding to the custom HTML tag <tg-slideshow>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockslideshow)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "slideshow" |
| blocks | Array of RichBlock | Yes | Elements of the slideshow |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
