# Type: MessageGenerationStopped

**Category**: Available types

**Description**: This object describes an update about a user stopping message generation.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messagegenerationstopped)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| chat | Chat | Yes | Chat in which the message is generated |
| message_thread_id | Integer | Optional | Optional. Unique identifier of the message thread in which the message is generated |
| draft_id | Integer | Yes | Unique identifier of the message draft which was stopped |
