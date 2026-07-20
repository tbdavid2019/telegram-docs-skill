# Type: InputRichBlockAnimation

**Category**: Rich messages

**Description**: A block with an animation, corresponding to the HTML tag <video>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockanimation)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "animation" |
| animation | InputMediaAnimation | Yes | The animation. Caption is ignored. |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
