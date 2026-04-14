# Type: BusinessConnection

**Category**: Available types

**Description**: Describes the connection of the bot with a business account.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#businessconnection)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique identifier of the business connection |
| user | User | Yes | Business account user that created the business connection |
| user_chat_id | Integer | Yes | Identifier of a private chat with the user who created the business connection. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. |
| date | Integer | Yes | Date the connection was established in Unix time |
| rights | BusinessBotRights | Optional | Optional. Rights of the business bot |
| is_enabled | Boolean | Yes | True, if the connection is active |
