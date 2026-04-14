# Method: setChatAdministratorCustomTitle

**Category**: Available methods

**Description**: Use this method to set a custom title for an administrator in a supergroup promoted by the bot. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setchatadministratorcustomtitle)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup (in the format @supergroupusername) |
| user_id | Integer | Yes | Unique identifier of the target user |
| custom_title | String | Yes | New custom title for the administrator; 0-16 characters, emoji are not allowed |
