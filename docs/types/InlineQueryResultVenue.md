# Type: InlineQueryResultVenue

**Category**: Inline mode

**Description**: Represents a venue. By default, the venue will be sent by the user. Alternatively, you can use input_message_content to send a message with the specified content instead of the venue.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultvenue)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be venue |
| id | String | Yes | Unique identifier for this result, 1-64 Bytes |
| latitude | Float | Yes | Latitude of the venue location in degrees |
| longitude | Float | Yes | Longitude of the venue location in degrees |
| title | String | Yes | Title of the venue |
| address | String | Yes | Address of the venue |
| foursquare_id | String | Optional | Optional. Foursquare identifier of the venue if known |
| foursquare_type | String | Optional | Optional. Foursquare type of the venue, if known. (For example, "arts_entertainment/default", "arts_entertainment/aquarium" or "food/icecream".) |
| google_place_id | String | Optional | Optional. Google Places identifier of the venue |
| google_place_type | String | Optional | Optional. Google Places type of the venue. (See supported types.) |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the venue |
| thumbnail_url | String | Optional | Optional. Url of the thumbnail for the result |
| thumbnail_width | Integer | Optional | Optional. Thumbnail width |
| thumbnail_height | Integer | Optional | Optional. Thumbnail height |
