# Type: RichBlockAnimation

**Category**: Rich messages

**Description**: A block with an animation, corresponding to the HTML tag <video>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockanimation)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "animation" |
| animation | Animation | Yes | The animation |
| has_spoiler | Boolean | Optional | Optional. True, if the media preview is covered by a spoiler animation |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
