# Type: MessageOriginUser

**Category**: Available types

**Description**: The message was originally sent by a known user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messageoriginuser)

**Subtype of**: MessageOrigin

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the message origin, always "user" |
| date | Integer | Yes | Date the message was sent originally in Unix time |
| sender_user | User | Yes | User that sent the message originally |
