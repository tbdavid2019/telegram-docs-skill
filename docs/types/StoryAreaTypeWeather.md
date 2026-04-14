# Type: StoryAreaTypeWeather

**Category**: Available types

**Description**: Describes a story area containing weather information. Currently, a story can have up to 3 weather areas.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#storyareatypeweather)

**Subtype of**: StoryAreaType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the area, always "weather" |
| temperature | Float | Yes | Temperature, in degree Celsius |
| emoji | String | Yes | Emoji representing the weather |
| background_color | Integer | Yes | A color of the area background in the ARGB format |
