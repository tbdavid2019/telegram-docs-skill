# Type: InlineQueryResultArticle

**Category**: Inline mode

**Description**: Represents a link to an article or web page.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultarticle)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be article |
| id | String | Yes | Unique identifier for this result, 1-64 Bytes |
| title | String | Yes | Title of the result |
| input_message_content | InputMessageContent | Yes | Content of the message to be sent |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| url | String | Optional | Optional. URL of the result |
| description | String | Optional | Optional. Short description of the result |
| thumbnail_url | String | Optional | Optional. Url of the thumbnail for the result |
| thumbnail_width | Integer | Optional | Optional. Thumbnail width |
| thumbnail_height | Integer | Optional | Optional. Thumbnail height |
