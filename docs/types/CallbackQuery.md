# Type: CallbackQuery

**Category**: Available types

**Description**: This object represents an incoming callback query from a callback button in an inline keyboard or in a rich message. If the button that originated the query belongs to a message sent by the bot, the field message will be present, unless the field inline_message_id is used instead as specified by the parameter callback_query_mode of the method setMySettings. If the button belongs to a message sent via the bot (in inline mode), the field inline_message_id will be present. Exactly one of the fields data or game_short_name will be present.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#callbackquery)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique identifier for this query |
| from | User | Yes | Sender |
| message | MaybeInaccessibleMessage | Optional | Optional. Message sent by the bot with the callback button that originated the query |
| inline_message_id | String | Optional | Optional. Identifier of the message sent via the bot in inline mode, that originated the query. Can also be present for messages sent by the bot, depending on the parameter callback_query_mode of the method setMySettings. |
| chat_instance | String | Yes | Global identifier, uniquely corresponding to the chat to which the message with the callback button was sent. Useful for high scores in games. |
| data | String | Optional | Optional. Data associated with the callback button. Be aware that the message that originated the query can contain no callback buttons with this data. |
| game_short_name | String | Optional | Optional. Short name of a Game to be returned, serves as the unique identifier for the game |
