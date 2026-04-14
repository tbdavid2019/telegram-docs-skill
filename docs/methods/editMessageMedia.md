# Method: editMessageMedia

**Category**: Updating messages

**Description**: Use this method to edit animation, audio, document, photo, or video messages, or to add media to text messages. If a message is part of a message album, then it can be edited only to an audio for audio albums, only to a document for document albums and to a photo or a video otherwise. When an inline message is edited, a new file can't be uploaded; use a previously uploaded file via its file_id or specify a URL. On success, if the edited message is not an inline message, the edited Message is returned, otherwise True is returned. Note that business messages that were not sent by the bot and do not contain an inline keyboard can only be edited within 48 hours from the time they were sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#editmessagemedia)

**Returns**: Message, Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Optional | Unique identifier of the business connection on behalf of which the message to be edited was sent |
| chat_id | Integer or String | Optional | Required if inline_message_id is not specified. Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| message_id | Integer | Optional | Required if inline_message_id is not specified. Identifier of the message to edit |
| inline_message_id | String | Optional | Required if chat_id and message_id are not specified. Identifier of the inline message |
| media | InputMedia | Yes | A JSON-serialized object for a new media content of the message |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for a new inline keyboard. |
