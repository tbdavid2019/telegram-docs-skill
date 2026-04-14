# Type: Game

**Category**: Games

**Description**: This object represents a game. Use BotFather to create and edit games, their short names will act as unique identifiers.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#game)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| title | String | Yes | Title of the game |
| description | String | Yes | Description of the game |
| photo | Array of PhotoSize | Yes | Photo that will be displayed in the game message in chats. |
| text | String | Optional | Optional. Brief description of the game or high scores included in the game message. Can be automatically edited to include current high scores for the game when the bot calls setGameScore, or manually edited using editMessageText. 0-4096 characters. |
| text_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in text, such as usernames, URLs, bot commands, etc. |
| animation | Animation | Optional | Optional. Animation that will be displayed in the game message in chats. Upload via BotFather |
