# Type: InputMediaLocation

**Category**: Available types

**Description**: Represents a location to be sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputmedialocation)

**Subtype of**: InputPollMedia, InputPollOptionMedia

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the media, must be location |
| latitude | Float | Yes | Latitude of the location |
| longitude | Float | Yes | Longitude of the location |
| horizontal_accuracy | Float | Optional | Optional. The radius of uncertainty for the location, measured in meters; 0-1500 |
