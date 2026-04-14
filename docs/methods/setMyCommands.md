# Method: setMyCommands

**Category**: Available methods

**Description**: Use this method to change the list of the bot's commands. See this manual for more details about bot commands. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setmycommands)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| commands | Array of BotCommand | Yes | A JSON-serialized list of bot commands to be set as the list of the bot's commands. At most 100 commands can be specified. |
| scope | BotCommandScope | Optional | A JSON-serialized object, describing scope of users for which the commands are relevant. Defaults to BotCommandScopeDefault. |
| language_code | String | Optional | A two-letter ISO 639-1 language code. If empty, commands will be applied to all users from the given scope, for whose language there are no dedicated commands |
