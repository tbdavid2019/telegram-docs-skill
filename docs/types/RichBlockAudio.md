# Type: RichBlockAudio

**Category**: Rich messages

**Description**: A block with a music file, corresponding to the HTML tag <audio>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockaudio)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "audio" |
| audio | Audio | Yes | The audio |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
