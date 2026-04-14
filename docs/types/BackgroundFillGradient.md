# Type: BackgroundFillGradient

**Category**: Available types

**Description**: The background is a gradient fill.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#backgroundfillgradient)

**Subtype of**: BackgroundFill

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the background fill, always "gradient" |
| top_color | Integer | Yes | Top color of the gradient in the RGB24 format |
| bottom_color | Integer | Yes | Bottom color of the gradient in the RGB24 format |
| rotation_angle | Integer | Yes | Clockwise rotation angle of the background fill in degrees; 0-359 |
