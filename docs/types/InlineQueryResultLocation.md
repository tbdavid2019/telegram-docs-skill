# Type: InlineQueryResultLocation

**Category**: Inline mode

**Description**: Represents a location on a map. By default, the location will be sent by the user. Alternatively, you can use input_message_content to send a message with the specified content instead of the location.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultlocation)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be location |
| id | String | Yes | Unique identifier for this result, 1-64 Bytes |
| latitude | Float | Yes | Location latitude in degrees |
| longitude | Float | Yes | Location longitude in degrees |
| title | String | Yes | Location title |
| horizontal_accuracy | Float | Optional | Optional. The radius of uncertainty for the location, measured in meters; 0-1500 |
| live_period | Integer | Optional | Optional. Period in seconds during which the location can be updated, should be between 60 and 86400, or 0x7FFFFFFF for live locations that can be edited indefinitely. |
| heading | Integer | Optional | Optional. For live locations, a direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. |
| proximity_alert_radius | Integer | Optional | Optional. For live locations, a maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the location |
| thumbnail_url | String | Optional | Optional. Url of the thumbnail for the result |
| thumbnail_width | Integer | Optional | Optional. Thumbnail width |
| thumbnail_height | Integer | Optional | Optional. Thumbnail height |
