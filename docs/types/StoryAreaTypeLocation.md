# Type: StoryAreaTypeLocation

**Category**: Available types

**Description**: Describes a story area pointing to a location. Currently, a story can have up to 10 location areas.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#storyareatypelocation)

**Subtype of**: StoryAreaType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the area, always "location" |
| latitude | Float | Yes | Location latitude in degrees |
| longitude | Float | Yes | Location longitude in degrees |
| address | LocationAddress | Optional | Optional. Address of the location |
