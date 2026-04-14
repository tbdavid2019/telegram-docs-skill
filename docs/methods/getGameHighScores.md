# Method: getGameHighScores

**Category**: Games

**Description**: Use this method to get data for high score tables. Will return the score of the specified user and several of their neighbors in a game. Returns an Array of GameHighScore objects.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getgamehighscores)

**Returns**: Array of GameHighScore

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| user_id | Integer | Yes | Target user id |
| chat_id | Integer | Optional | Required if inline_message_id is not specified. Unique identifier for the target chat |
| message_id | Integer | Optional | Required if inline_message_id is not specified. Identifier of the sent message |
| inline_message_id | String | Optional | Required if chat_id and message_id are not specified. Identifier of the inline message |
