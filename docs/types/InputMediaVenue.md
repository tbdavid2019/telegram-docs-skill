# Type: InputMediaVenue

**Category**: Available types

**Description**: Represents a venue to be sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputmediavenue)

**Subtype of**: InputPollMedia, InputPollOptionMedia

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the media, must be venue |
| latitude | Float | Yes | Latitude of the location |
| longitude | Float | Yes | Longitude of the location |
| title | String | Yes | Name of the venue |
| address | String | Yes | Address of the venue |
| foursquare_id | String | Optional | Optional. Foursquare identifier of the venue |
| foursquare_type | String | Optional | Optional. Foursquare type of the venue, if known. (For example, "arts_entertainment/default", "arts_entertainment/aquarium" or "food/icecream".) |
| google_place_id | String | Optional | Optional. Google Places identifier of the venue |
| google_place_type | String | Optional | Optional. Google Places type of the venue. (See supported types.) |
