# Method: setChatMenuButton

**Category**: Available methods

**Description**: Use this method to change the bot's menu button in a private chat, or the default menu button. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setchatmenubutton)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer | Optional | Unique identifier for the target private chat. If not specified, default bot's menu button will be changed |
| menu_button | MenuButton | Optional | A JSON-serialized object for the bot's new menu button. Defaults to MenuButtonDefault |
