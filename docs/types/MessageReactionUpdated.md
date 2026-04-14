# Type: MessageReactionUpdated

**Category**: Available types

**Description**: This object represents a change of a reaction on a message performed by a user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messagereactionupdated)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| chat | Chat | Yes | The chat containing the message the user reacted to |
| message_id | Integer | Yes | Unique identifier of the message inside the chat |
| user | User | Optional | Optional. The user that changed the reaction, if the user isn't anonymous |
| actor_chat | Chat | Optional | Optional. The chat on behalf of which the reaction was changed, if the user is anonymous |
| date | Integer | Yes | Date of the change in Unix time |
| old_reaction | Array of ReactionType | Yes | Previous list of reaction types that were set by the user |
| new_reaction | Array of ReactionType | Yes | New list of reaction types that have been set by the user |
