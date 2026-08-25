# Type: InlineKeyboardMarkup

**Category**: Available types

**Description**: This object represents an inline keyboard that appears right next to the message it belongs to.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinekeyboardmarkup)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| inline_keyboard | Array of Array of InlineKeyboardButton | Yes | Array of button rows, each represented by an Array of InlineKeyboardButton objects |
| force_reply | Boolean | Optional | Optional. Pass True if the reply interface must be shown to the user, as if they had manually selected the bot's message and tapped 'Reply'. The value of the field can't be changed when the inline keyboard is edited. |
