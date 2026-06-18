# Method: sendMessageDraft

**Category**: Available methods

**Description**: Use this method to stream a partial message to a user while the message is being generated. Note that the streamed draft is ephemeral and acts as a temporary 30-second preview - once the output is finalized, you must call sendMessage with the complete message to persist it in the user's chat. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sendmessagedraft)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer | Yes | Unique identifier for the target private chat |
| message_thread_id | Integer | Optional | Unique identifier for the target message thread |
| draft_id | Integer | Yes | Unique identifier of the message draft; must be non-zero. Changes to drafts with the same identifier are animated. |
| text | String | Optional | Text of the message to be sent, 0-4096 characters after entities parsing. Pass an empty text to show a "Thinking..." placeholder. |
| parse_mode | String | Optional | Mode for parsing entities in the message text. See formatting options for more details. |
| entities | Array of MessageEntity | Optional | A JSON-serialized list of special entities that appear in message text, which can be specified instead of parse_mode |
