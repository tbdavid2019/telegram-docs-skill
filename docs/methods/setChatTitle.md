# Method: setChatTitle

**Category**: Available methods

**Description**: Use this method to change the title of a chat. Titles can't be changed for private chats. The bot must be an administrator in the chat for this to work and must have the appropriate administrator rights. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setchattitle)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| title | String | Yes | New chat title, 1-128 characters |
