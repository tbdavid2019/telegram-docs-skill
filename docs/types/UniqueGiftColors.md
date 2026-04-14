# Type: UniqueGiftColors

**Category**: Available types

**Description**: This object contains information about the color scheme for a user's name, message replies and link previews based on a unique gift.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#uniquegiftcolors)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| model_custom_emoji_id | String | Yes | Custom emoji identifier of the unique gift's model |
| symbol_custom_emoji_id | String | Yes | Custom emoji identifier of the unique gift's symbol |
| light_theme_main_color | Integer | Yes | Main color used in light themes; RGB format |
| light_theme_other_colors | Array of Integer | Yes | List of 1-3 additional colors used in light themes; RGB format |
| dark_theme_main_color | Integer | Yes | Main color used in dark themes; RGB format |
| dark_theme_other_colors | Array of Integer | Yes | List of 1-3 additional colors used in dark themes; RGB format |
