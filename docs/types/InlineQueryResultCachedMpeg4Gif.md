# Type: InlineQueryResultCachedMpeg4Gif

**Category**: Inline mode

**Description**: Represents a link to a video animation (H.264/MPEG-4 AVC video without sound) stored on the Telegram servers. By default, this animated MPEG-4 file will be sent by the user with an optional caption. Alternatively, you can use input_message_content to send a message with the specified content instead of the animation.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultcachedmpeg4gif)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be mpeg4_gif |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| mpeg4_file_id | String | Yes | A valid file identifier for the MPEG4 file |
| title | String | Optional | Optional. Title for the result |
| caption | String | Optional | Optional. Caption of the MPEG-4 file to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| show_caption_above_media | Boolean | Optional | Optional. Pass True, if the caption must be shown above the message media |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the video animation |
