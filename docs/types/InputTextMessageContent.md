# Type: InputTextMessageContent

**Category**: Inline mode

**Description**: Represents the content of a text message to be sent as the result of an inline query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputtextmessagecontent)

**Subtype of**: InputMessageContent

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| message_text | String | Yes | Text of the message to be sent, 1-4096 characters |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the message text. See formatting options for more details. |
| entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in message text, which can be specified instead of parse_mode |
| link_preview_options | LinkPreviewOptions | Optional | Optional. Link preview generation options for the message |
