# Type: InlineQueryResultGame

**Category**: Inline mode

**Description**: Represents a Game.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultgame)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be game |
| id | String | Yes | Unique identifier for this result, 1-64 bytes |
| game_short_name | String | Yes | Short name of the game |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
