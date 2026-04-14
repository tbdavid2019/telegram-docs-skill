# Type: InlineQueryResultGif

**Category**: Inline mode

**Description**: Represents a link to an animated GIF file. By default, this animated GIF file will be sent by the user with optional caption. Alternatively, you can use input_message_content to send a message with the specified content instead of the animation.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultgif)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be gif |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| gif_url | String | Yes | A valid URL for the GIF file |
| gif_width | Integer | Optional | Optional. Width of the GIF |
| gif_height | Integer | Optional | Optional. Height of the GIF |
| gif_duration | Integer | Optional | Optional. Duration of the GIF in seconds |
| thumbnail_url | String | Yes | URL of the static (JPEG or GIF) or animated (MPEG4) thumbnail for the result |
| thumbnail_mime_type | String | Optional | Optional. MIME type of the thumbnail, must be one of "image/jpeg", "image/gif", or "video/mp4". Defaults to "image/jpeg" |
| title | String | Optional | Optional. Title for the result |
| caption | String | Optional | Optional. Caption of the GIF file to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| show_caption_above_media | Boolean | Optional | Optional. Pass True, if the caption must be shown above the message media |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the GIF animation |
