# Method: setMyDescription

**Category**: Available methods

**Description**: Use this method to change the bot's description, which is shown in the chat with the bot if the chat is empty. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setmydescription)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| description | String | Optional | New bot description; 0-512 characters. Pass an empty string to remove the dedicated description for the given language. |
| language_code | String | Optional | A two-letter ISO 639-1 language code. If empty, the description will be applied to all users for whose language there is no dedicated description. |
