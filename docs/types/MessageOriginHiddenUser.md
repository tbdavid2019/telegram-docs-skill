# Type: MessageOriginHiddenUser

**Category**: Available types

**Description**: The message was originally sent by an unknown user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messageoriginhiddenuser)

**Subtype of**: MessageOrigin

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the message origin, always "hidden_user" |
| date | Integer | Yes | Date the message was sent originally in Unix time |
| sender_user_name | String | Yes | Name of the user that sent the message originally |
