# Type: ChatShareThemeEmoji

**Category**: Available types

**Description**: The theme with emoji placed on a background.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatsharethemeemoji)

**Subtype of**: ChatShareTheme

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the theme, always "emoji" |
| emojis | Array of EmojiType | Yes | The emoji; 0-6 regular or custom emoji |
| background_backdrop_id | Integer | Optional | Optional. Identifier of the backdrop used as the background; omitted if the default background is used. Use getChatShareThemeBackdrops to get details about the backdrop. |
