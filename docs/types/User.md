# Type: User

**Category**: Available types

**Description**: This object represents a Telegram user or bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#user)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | Integer | Yes | Unique identifier for this user or bot. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type is safe for storing this identifier. |
| is_bot | Boolean | Yes | True, if this user is a bot |
| first_name | String | Yes | User's or bot's first name |
| last_name | String | Optional | Optional. User's or bot's last name |
| username | String | Optional | Optional. User's or bot's username |
| language_code | String | Optional | Optional. IETF language tag of the user's language |
| is_premium | Boolean | Optional | Optional. True, if this user is a Telegram Premium user |
| added_to_attachment_menu | Boolean | Optional | Optional. True, if this user added the bot to the attachment menu |
