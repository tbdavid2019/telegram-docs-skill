# Type: InputRichBlockVoiceNote

**Category**: Rich messages

**Description**: A block with a voice note, corresponding to the HTML tag <audio>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockvoicenote)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "voice_note" |
| voice_note | InputMediaVoiceNote | Yes | The voice note. Caption is ignored. |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
