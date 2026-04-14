# Type: MessageReactionCountUpdated

**Category**: Available types

**Description**: This object represents reaction changes on a message with anonymous reactions.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messagereactioncountupdated)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| chat | Chat | Yes | The chat containing the message |
| message_id | Integer | Yes | Unique message identifier inside the chat |
| date | Integer | Yes | Date of the change in Unix time |
| reactions | Array of ReactionCount | Yes | List of reactions that are present on the message |
