# Method: createChatSubscriptionInviteLink

**Category**: Available methods

**Description**: Use this method to create a subscription invite link for a channel chat. The bot must have the can_invite_users administrator rights. The link can be edited using the method editChatSubscriptionInviteLink or revoked using the method revokeChatInviteLink. Returns the new invite link as a ChatInviteLink object.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#createchatsubscriptioninvitelink)

**Returns**: ChatInviteLink

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target channel chat or username of the target channel (in the format @channelusername) |
| name | String | Optional | Invite link name; 0-32 characters |
| subscription_period | Integer | Yes | The number of seconds the subscription will be active for before the next payment. Currently, it must always be 2592000 (30 days). |
| subscription_price | Integer | Yes | The amount of Telegram Stars a user must pay initially and after each subsequent subscription period to be a member of the chat; 1-10000 |
