# Method: verifyChat

**Category**: Available methods

**Description**: Verifies a chat on behalf of the organization which is represented by the bot. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#verifychat)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername). Channel direct messages chats can't be verified. |
| custom_description | String | Optional | Custom description for the verification; 0-70 characters. Must be empty if the organization isn't allowed to provide a custom verification description. |
