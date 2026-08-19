# Type: InputRichBlockAudio

**Category**: Rich messages

**Description**: A block with a music file, corresponding to the HTML tag <audio>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockaudio)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "audio" |
| audio | InputMediaAudio | Yes | The audio. Caption is ignored. |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
