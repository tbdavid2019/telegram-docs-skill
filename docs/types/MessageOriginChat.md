# Type: MessageOriginChat

**Category**: Available types

**Description**: The message was originally sent on behalf of a chat to a group chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messageoriginchat)

**Subtype of**: MessageOrigin

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the message origin, always "chat" |
| date | Integer | Yes | Date the message was sent originally in Unix time |
| sender_chat | Chat | Yes | Chat that sent the message originally |
| author_signature | String | Optional | Optional. For messages originally sent by an anonymous chat administrator, original message author signature |
