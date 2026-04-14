# Type: InlineQueryResultCachedVoice

**Category**: Inline mode

**Description**: Represents a link to a voice message stored on the Telegram servers. By default, this voice message will be sent by the user. Alternatively, you can use input_message_content to send a message with the specified content instead of the voice message.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultcachedvoice)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be voice |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| voice_file_id | String | Yes | A valid file identifier for the voice message |
| title | String | Yes | Voice message title |
| caption | String | Optional | Optional. Caption, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the voice message caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the voice message |
