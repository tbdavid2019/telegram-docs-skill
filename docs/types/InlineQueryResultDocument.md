# Type: InlineQueryResultDocument

**Category**: Inline mode

**Description**: Represents a link to a file. By default, this file will be sent by the user with an optional caption. Alternatively, you can use input_message_content to send a message with the specified content instead of the file. Currently, only .PDF and .ZIP files can be sent using this method.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultdocument)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be document |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| title | String | Yes | Title for the result |
| caption | String | Optional | Optional. Caption of the document to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the document caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| document_url | String | Yes | A valid URL for the file |
| mime_type | String | Yes | MIME type of the content of the file, either "application/pdf" or "application/zip" |
| description | String | Optional | Optional. Short description of the result |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the file |
| thumbnail_url | String | Optional | Optional. URL of the thumbnail (JPEG only) for the file |
| thumbnail_width | Integer | Optional | Optional. Thumbnail width |
| thumbnail_height | Integer | Optional | Optional. Thumbnail height |
