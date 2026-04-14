# Method: sendMessageDraft

**Category**: Available methods

**Description**: Use this method to stream a partial message to a user while the message is being generated. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sendmessagedraft)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer | Yes | Unique identifier for the target private chat |
| message_thread_id | Integer | Optional | Unique identifier for the target message thread |
| draft_id | Integer | Yes | Unique identifier of the message draft; must be non-zero. Changes of drafts with the same identifier are animated |
| text | String | Yes | Text of the message to be sent, 1-4096 characters after entities parsing |
| parse_mode | String | Optional | Mode for parsing entities in the message text. See formatting options for more details. |
| entities | Array of MessageEntity | Optional | A JSON-serialized list of special entities that appear in message text, which can be specified instead of parse_mode |
