# Method: revokeChatInviteLink

**Category**: Available methods

**Description**: Use this method to revoke an invite link created by the bot. If the primary link is revoked, a new link is automatically generated. The bot must be an administrator in the chat for this to work and must have the appropriate administrator rights. Returns the revoked invite link as ChatInviteLink object.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#revokechatinvitelink)

**Returns**: ChatInviteLink

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier of the target chat or username of the target channel (in the format @channelusername) |
| invite_link | String | Yes | The invite link to revoke |
