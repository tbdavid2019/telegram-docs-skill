# Type: InputRichBlockCollage

**Category**: Rich messages

**Description**: A collage, corresponding to the custom HTML tag <tg-collage>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockcollage)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "collage" |
| blocks | Array of InputRichBlock | Yes | Elements of the collage |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
