# Method: editMessageText

**Category**: Updating messages

**Description**: Use this method to edit text and game messages. On success, if the edited message is not an inline message, the edited Message is returned, otherwise True is returned. Note that business messages that were not sent by the bot and do not contain an inline keyboard can only be edited within 48 hours from the time they were sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#editmessagetext)

**Returns**: Message, Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Optional | Unique identifier of the business connection on behalf of which the message to be edited was sent |
| chat_id | Integer or String | Optional | Required if inline_message_id is not specified. Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| message_id | Integer | Optional | Required if inline_message_id is not specified. Identifier of the message to edit |
| inline_message_id | String | Optional | Required if chat_id and message_id are not specified. Identifier of the inline message |
| text | String | Yes | New text of the message, 1-4096 characters after entities parsing |
| parse_mode | String | Optional | Mode for parsing entities in the message text. See formatting options for more details. |
| entities | Array of MessageEntity | Optional | A JSON-serialized list of special entities that appear in message text, which can be specified instead of parse_mode |
| link_preview_options | LinkPreviewOptions | Optional | Link preview generation options for the message |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for an inline keyboard. |
