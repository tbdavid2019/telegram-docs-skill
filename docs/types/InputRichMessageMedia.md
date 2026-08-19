# Type: InputRichMessageMedia

**Category**: Rich messages

**Description**: Describes a media element embedded in an outgoing rich message.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichmessagemedia)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique identifier of the media used in a tg://photo?id=, tg://video?id=, or tg://audio?id= link. 1-64 characters, only A-Z, a-z, 0-9, _ and - are allowed. |
| media | InputMediaAnimation or InputMediaAudio or InputMediaPhoto or InputMediaVideo or InputMediaVoiceNote | Yes | The media to be sent. Everything except the media itself and its properties is ignored. |
