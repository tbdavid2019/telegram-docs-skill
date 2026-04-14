# Type: WebAppData

**Category**: Available types

**Description**: Describes data sent from a Web App to the bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#webappdata)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| data | String | Yes | The data. Be aware that a bad client can send arbitrary data in this field. |
| button_text | String | Yes | Text of the web_app keyboard button from which the Web App was opened. Be aware that a bad client can send arbitrary data in this field. |
