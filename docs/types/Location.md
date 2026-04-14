# Type: Location

**Category**: Available types

**Description**: This object represents a point on the map.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#location)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| latitude | Float | Yes | Latitude as defined by the sender |
| longitude | Float | Yes | Longitude as defined by the sender |
| horizontal_accuracy | Float | Optional | Optional. The radius of uncertainty for the location, measured in meters; 0-1500 |
| live_period | Integer | Optional | Optional. Time relative to the message sending date, during which the location can be updated; in seconds. For active live locations only. |
| heading | Integer | Optional | Optional. The direction in which user is moving, in degrees; 1-360. For active live locations only. |
| proximity_alert_radius | Integer | Optional | Optional. The maximum distance for proximity alerts about approaching another chat member, in meters. For sent live locations only. |
