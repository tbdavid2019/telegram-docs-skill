# Method: getMyCommands

**Category**: Available methods

**Description**: Use this method to get the current list of the bot's commands for the given scope and user language. Returns an Array of BotCommand objects. If commands aren't set, an empty list is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getmycommands)

**Returns**: Array of BotCommand

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| scope | BotCommandScope | Optional | A JSON-serialized object, describing scope of users. Defaults to BotCommandScopeDefault. |
| language_code | String | Optional | A two-letter ISO 639-1 language code or an empty string |
