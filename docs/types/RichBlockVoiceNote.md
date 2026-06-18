# Type: RichBlockVoiceNote

**Category**: Rich messages

**Description**: A block with a voice note, corresponding to the HTML tag <audio>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockvoicenote)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "voice_note" |
| voice_note | Voice | Yes | The voice note |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
