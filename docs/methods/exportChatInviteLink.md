# Method: exportChatInviteLink

**Category**: Available methods

**Description**: Use this method to generate a new primary invite link for a chat; any previously generated primary link is revoked. The bot must be an administrator in the chat for this to work and must have the appropriate administrator rights. Returns the new invite link as String on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#exportchatinvitelink)

**Returns**: String

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
