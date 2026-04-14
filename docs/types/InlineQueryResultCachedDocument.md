# Type: InlineQueryResultCachedDocument

**Category**: Inline mode

**Description**: Represents a link to a file stored on the Telegram servers. By default, this file will be sent by the user with an optional caption. Alternatively, you can use input_message_content to send a message with the specified content instead of the file.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultcacheddocument)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be document |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| title | String | Yes | Title for the result |
| document_file_id | String | Yes | A valid file identifier for the file |
| description | String | Optional | Optional. Short description of the result |
| caption | String | Optional | Optional. Caption of the document to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the document caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the file |
