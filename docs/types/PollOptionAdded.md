# Type: PollOptionAdded

**Category**: Available types

**Description**: Describes a service message about an option added to a poll.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#polloptionadded)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| poll_message | MaybeInaccessibleMessage | Optional | Optional. Message containing the poll to which the option was added, if known. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| option_persistent_id | String | Yes | Unique identifier of the added option |
| option_text | String | Yes | Option text |
| option_text_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the option_text |
