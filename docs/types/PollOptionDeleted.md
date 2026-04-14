# Type: PollOptionDeleted

**Category**: Available types

**Description**: Describes a service message about an option deleted from a poll.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#polloptiondeleted)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| poll_message | MaybeInaccessibleMessage | Optional | Optional. Message containing the poll from which the option was deleted, if known. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| option_persistent_id | String | Yes | Unique identifier of the deleted option |
| option_text | String | Yes | Option text |
| option_text_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the option_text |
