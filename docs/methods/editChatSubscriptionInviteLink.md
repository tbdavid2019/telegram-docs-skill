# Method: editChatSubscriptionInviteLink

**Category**: Available methods

**Description**: Use this method to edit a subscription invite link created by the bot. The bot must have the can_invite_users administrator rights. Returns the edited invite link as a ChatInviteLink object.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#editchatsubscriptioninvitelink)

**Returns**: ChatInviteLink

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| invite_link | String | Yes | The invite link to edit |
| name | String | Optional | Invite link name; 0-32 characters |
