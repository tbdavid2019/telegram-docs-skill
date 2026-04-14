# Method: deleteMyCommands

**Category**: Available methods

**Description**: Use this method to delete the list of the bot's commands for the given scope and user language. After deletion, higher level commands will be shown to affected users. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#deletemycommands)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| scope | BotCommandScope | Optional | A JSON-serialized object, describing scope of users for which the commands are relevant. Defaults to BotCommandScopeDefault. |
| language_code | String | Optional | A two-letter ISO 639-1 language code. If empty, commands will be applied to all users from the given scope, for whose language there are no dedicated commands |
