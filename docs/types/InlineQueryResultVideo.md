# Type: InlineQueryResultVideo

**Category**: Inline mode

**Description**: Represents a link to a page containing an embedded video player or a video file. By default, this video file will be sent by the user with an optional caption. Alternatively, you can use input_message_content to send a message with the specified content instead of the video.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultvideo)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be video |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| video_url | String | Yes | A valid URL for the embedded video player or video file |
| mime_type | String | Yes | MIME type of the content of the video URL, "text/html" or "video/mp4" |
| thumbnail_url | String | Yes | URL of the thumbnail (JPEG only) for the video |
| title | String | Yes | Title for the result |
| caption | String | Optional | Optional. Caption of the video to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the video caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| show_caption_above_media | Boolean | Optional | Optional. Pass True, if the caption must be shown above the message media |
| video_width | Integer | Optional | Optional. Video width |
| video_height | Integer | Optional | Optional. Video height |
| video_duration | Integer | Optional | Optional. Video duration in seconds |
| description | String | Optional | Optional. Short description of the result |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the video. This field is required if InlineQueryResultVideo is used to send an HTML-page as a result (e.g., a YouTube video). |
