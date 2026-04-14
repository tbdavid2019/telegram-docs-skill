# Type: User

**Category**: Available types

**Description**: This object represents a Telegram user or bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#user)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | Integer | Yes | Unique identifier for this user or bot. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. |
| is_bot | Boolean | Yes | True, if this user is a bot |
| first_name | String | Yes | User's or bot's first name |
| last_name | String | Optional | Optional. User's or bot's last name |
| username | String | Optional | Optional. User's or bot's username |
| language_code | String | Optional | Optional. IETF language tag of the user's language |
| is_premium | Boolean | Optional | Optional. True, if this user is a Telegram Premium user |
| added_to_attachment_menu | Boolean | Optional | Optional. True, if this user added the bot to the attachment menu |
| can_join_groups | Boolean | Optional | Optional. True, if the bot can be invited to groups. Returned only in getMe. |
| can_read_all_group_messages | Boolean | Optional | Optional. True, if privacy mode is disabled for the bot. Returned only in getMe. |
| supports_inline_queries | Boolean | Optional | Optional. True, if the bot supports inline queries. Returned only in getMe. |
| can_connect_to_business | Boolean | Optional | Optional. True, if the bot can be connected to a Telegram Business account to receive its messages. Returned only in getMe. |
| has_main_web_app | Boolean | Optional | Optional. True, if the bot has a main Web App. Returned only in getMe. |
| has_topics_enabled | Boolean | Optional | Optional. True, if the bot has forum topic mode enabled in private chats. Returned only in getMe. |
| allows_users_to_create_topics | Boolean | Optional | Optional. True, if the bot allows users to create and delete topics in private chats. Returned only in getMe. |
| can_manage_bots | Boolean | Optional | Optional. True, if other bots can be created to be controlled by the bot. Returned only in getMe. |
