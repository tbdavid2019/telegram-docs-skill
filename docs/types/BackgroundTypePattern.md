# Type: BackgroundTypePattern

**Category**: Available types

**Description**: The background is a .PNG or .TGV (gzipped subset of SVG with MIME type "application/x-tgwallpattern") pattern to be combined with the background fill chosen by the user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#backgroundtypepattern)

**Subtype of**: BackgroundType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the background, always "pattern" |
| document | Document | Yes | Document with the pattern |
| fill | BackgroundFill | Yes | The background fill that is combined with the pattern |
| intensity | Integer | Yes | Intensity of the pattern when it is shown above the filled background; 0-100 |
| is_inverted | Boolean | Optional | Optional. True, if the background fill must be applied only to the pattern itself. All other pixels are black in this case. For dark themes only |
| is_moving | Boolean | Optional | Optional. True, if the background moves slightly when the device is tilted |
