# Method: setChatPhoto

**Category**: Available methods

**Description**: Use this method to set a new profile photo for the chat. Photos can't be changed for private chats. The bot must be an administrator in the chat for this to work and must have the appropriate administrator rights. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setchatphoto)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| photo | InputFile | Yes | New chat photo, uploaded using multipart/form-data |
