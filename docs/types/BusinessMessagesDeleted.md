# Type: BusinessMessagesDeleted

**Category**: Available types

**Description**: This object is received when messages are deleted from a connected business account.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#businessmessagesdeleted)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection |
| chat | Chat | Yes | Information about a chat in the business account. The bot may not have access to the chat or the corresponding user. |
| message_ids | Array of Integer | Yes | The list of identifiers of deleted messages in the chat of the business account |
