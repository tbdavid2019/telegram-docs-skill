# Type: BackgroundTypeWallpaper

**Category**: Available types

**Description**: The background is a wallpaper in the JPEG format.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#backgroundtypewallpaper)

**Subtype of**: BackgroundType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the background, always "wallpaper" |
| document | Document | Yes | Document with the wallpaper |
| dark_theme_dimming | Integer | Yes | Dimming of the background in dark themes, as a percentage; 0-100 |
| is_blurred | Boolean | Optional | Optional. True, if the wallpaper is downscaled to fit in a 450x450 square and then box-blurred with radius 12 |
| is_moving | Boolean | Optional | Optional. True, if the background moves slightly when the device is tilted |
