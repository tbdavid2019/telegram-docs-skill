# Method: deleteForumTopic

**Category**: Available methods

**Description**: Use this method to delete a forum topic along with all its messages in a forum supergroup chat or a private chat with a user. In the case of a supergroup chat the bot must be an administrator in the chat for this to work and must have the can_delete_messages administrator rights. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#deleteforumtopic)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup (in the format @supergroupusername) |
| message_thread_id | Integer | Yes | Unique identifier for the target message thread of the forum topic |
