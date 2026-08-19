# Type: InputRichBlockVideo

**Category**: Rich messages

**Description**: A block with a video, corresponding to the HTML tag <video>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockvideo)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "video" |
| video | InputMediaVideo | Yes | The video. Caption is ignored. |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
