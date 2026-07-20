# Type: BotAccessSettings

**Category**: Available types

**Description**: This object describes the access settings of a bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#botaccesssettings)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| is_access_restricted | Boolean | Yes | True, if only selected users can access the bot. The bot's owner can always access it. |
| added_users | Array of User | Optional | Optional. The list of other users who have access to the bot if the access is restricted |
