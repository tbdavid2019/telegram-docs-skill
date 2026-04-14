# Method: sendGame

**Category**: Games

**Description**: Use this method to send a game. On success, the sent Message is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sendgame)

**Returns**: Message

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Optional | Unique identifier of the business connection on behalf of which the message will be sent |
| chat_id | Integer | Yes | Unique identifier for the target chat. Games can't be sent to channel direct messages chats and channel chats. |
| message_thread_id | Integer | Optional | Unique identifier for the target message thread (topic) of a forum; for forum supergroups and private chats of bots with forum topic mode enabled only |
| game_short_name | String | Yes | Short name of the game, serves as the unique identifier for the game. Set up your games via @BotFather. |
| disable_notification | Boolean | Optional | Sends the message silently. Users will receive a notification with no sound. |
| protect_content | Boolean | Optional | Protects the contents of the sent message from forwarding and saving |
| allow_paid_broadcast | Boolean | Optional | Pass True to allow up to 1000 messages per second, ignoring broadcasting limits for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot's balance |
| message_effect_id | String | Optional | Unique identifier of the message effect to be added to the message; for private chats only |
| reply_parameters | ReplyParameters | Optional | Description of the message to reply to |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for an inline keyboard. If empty, one 'Play game_title' button will be shown. If not empty, the first button must launch the game. |
