# Type: ManagedBotUpdated

**Category**: Available types

**Description**: This object contains information about the creation, token update, or owner update of a bot that is managed by the current bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#managedbotupdated)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| user | User | Yes | User that created the bot |
| bot | User | Yes | Information about the bot. Token of the bot can be fetched using the method getManagedBotToken. |
