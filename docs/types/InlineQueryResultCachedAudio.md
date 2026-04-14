# Type: InlineQueryResultCachedAudio

**Category**: Inline mode

**Description**: Represents a link to an MP3 audio file stored on the Telegram servers. By default, this audio file will be sent by the user. Alternatively, you can use input_message_content to send a message with the specified content instead of the audio.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultcachedaudio)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be audio |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| audio_file_id | String | Yes | A valid file identifier for the audio file |
| caption | String | Optional | Optional. Caption, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the audio caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the audio |
