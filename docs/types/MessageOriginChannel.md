# Type: MessageOriginChannel

**Category**: Available types

**Description**: The message was originally sent to a channel chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messageoriginchannel)

**Subtype of**: MessageOrigin

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the message origin, always "channel" |
| date | Integer | Yes | Date the message was sent originally in Unix time |
| chat | Chat | Yes | Channel chat to which the message was originally sent |
| message_id | Integer | Yes | Unique message identifier inside the chat |
| author_signature | String | Optional | Optional. Signature of the original post author |
