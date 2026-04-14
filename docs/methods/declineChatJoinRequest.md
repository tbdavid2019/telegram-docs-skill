# Method: declineChatJoinRequest

**Category**: Available methods

**Description**: Use this method to decline a chat join request. The bot must be an administrator in the chat for this to work and must have the can_invite_users administrator right. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#declinechatjoinrequest)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| user_id | Integer | Yes | Unique identifier of the target user |
