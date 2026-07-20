# Method: editEphemeralMessageMedia

**Category**: Updating messages

**Description**: Use this method to edit the media of an ephemeral message. Note that it is not guaranteed that the user will receive the message edit event, especially if they are offline. On success, True is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#editephemeralmessagemedia)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup in the format @username |
| receiver_user_id | Integer | Yes | Identifier of the user who received the message |
| ephemeral_message_id | Integer | Yes | Identifier of the ephemeral message to edit |
| media | InputMedia | Yes | A JSON-serialized object for the new media content of the message. A new file can't be uploaded; use a previously uploaded file via its file_id or specify a URL. |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for an inline keyboard |
