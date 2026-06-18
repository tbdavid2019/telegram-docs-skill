# Method: getUserPersonalChatMessages

**Category**: Available methods

**Description**: Use this method to get the last messages from the personal chat (i.e., the chat currently added to their profile) of a given user. On success, an array of Message objects is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getuserpersonalchatmessages)

**Returns**: Array of Message

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| user_id | Integer | Yes | Unique identifier for the target user |
| limit | Integer | Yes | The maximum number of messages to return; 1-20 |
