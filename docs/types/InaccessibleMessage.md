# Type: InaccessibleMessage

**Category**: Available types

**Description**: This object describes a message that was deleted or is otherwise inaccessible to the bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inaccessiblemessage)

**Subtype of**: MaybeInaccessibleMessage

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| chat | Chat | Yes | Chat the message belonged to |
| message_id | Integer | Yes | Unique message identifier inside the chat |
| date | Integer | Yes | Always 0. The field can be used to differentiate regular and inaccessible messages. |
