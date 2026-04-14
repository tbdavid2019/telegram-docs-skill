# Method: sendMediaGroup

**Category**: Available methods

**Description**: Use this method to send a group of photos, videos, documents or audios as an album. Documents and audio files can be only grouped in an album with messages of the same type. On success, an array of Message objects that were sent is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sendmediagroup)

**Returns**: Array of Message

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Optional | Unique identifier of the business connection on behalf of which the message will be sent |
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| message_thread_id | Integer | Optional | Unique identifier for the target message thread (topic) of a forum; for forum supergroups and private chats of bots with forum topic mode enabled only |
| direct_messages_topic_id | Integer | Optional | Identifier of the direct messages topic to which the messages will be sent; required if the messages are sent to a direct messages chat |
| media | Array of InputMediaAudio or Array of InputMediaDocument or Array of InputMediaPhoto or Array of InputMediaVideo | Yes | A JSON-serialized array describing messages to be sent, must include 2-10 items |
| disable_notification | Boolean | Optional | Sends messages silently. Users will receive a notification with no sound. |
| protect_content | Boolean | Optional | Protects the contents of the sent messages from forwarding and saving |
| allow_paid_broadcast | Boolean | Optional | Pass True to allow up to 1000 messages per second, ignoring broadcasting limits for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot's balance |
| message_effect_id | String | Optional | Unique identifier of the message effect to be added to the message; for private chats only |
| reply_parameters | ReplyParameters | Optional | Description of the message to reply to |
