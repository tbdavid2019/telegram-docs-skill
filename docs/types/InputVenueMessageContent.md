# Type: InputVenueMessageContent

**Category**: Inline mode

**Description**: Represents the content of a venue message to be sent as the result of an inline query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputvenuemessagecontent)

**Subtype of**: InputMessageContent

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| latitude | Float | Yes | Latitude of the venue in degrees |
| longitude | Float | Yes | Longitude of the venue in degrees |
| title | String | Yes | Name of the venue |
| address | String | Yes | Address of the venue |
| foursquare_id | String | Optional | Optional. Foursquare identifier of the venue, if known |
| foursquare_type | String | Optional | Optional. Foursquare type of the venue, if known. (For example, "arts_entertainment/default", "arts_entertainment/aquarium" or "food/icecream".) |
| google_place_id | String | Optional | Optional. Google Places identifier of the venue |
| google_place_type | String | Optional | Optional. Google Places type of the venue. (See supported types.) |
