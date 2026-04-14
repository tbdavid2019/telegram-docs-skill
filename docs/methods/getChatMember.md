# Method: getChatMember

**Category**: Available methods

**Description**: Use this method to get information about a member of a chat. The method is only guaranteed to work for other users if the bot is an administrator in the chat. Returns a ChatMember object on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getchatmember)

**Returns**: ChatMember

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup or channel (in the format @channelusername) |
| user_id | Integer | Yes | Unique identifier of the target user |
