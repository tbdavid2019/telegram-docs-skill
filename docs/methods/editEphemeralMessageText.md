# Method: editEphemeralMessageText

**Category**: Updating messages

**Description**: Use this method to edit an ephemeral text message. Note that it is not guaranteed that the user will receive the message edit event, especially if they are offline. On success, True is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#editephemeralmessagetext)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup in the format @username |
| receiver_user_id | Integer | Yes | Identifier of the user who received the message |
| ephemeral_message_id | Integer | Yes | Identifier of the ephemeral message to edit |
| text | String | Yes | New text of the message, 1-4096 characters after entity parsing |
| parse_mode | String | Optional | Mode for parsing entities in the message text. See formatting options for more details. |
| entities | Array of MessageEntity | Optional | A JSON-serialized list of special entities that appear in message text, which can be specified instead of parse_mode |
| link_preview_options | LinkPreviewOptions | Optional | Link preview generation options for the message |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for an inline keyboard |
