# Type: PollOption

**Category**: Available types

**Description**: This object contains information about one answer option in a poll.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#polloption)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| persistent_id | String | Yes | Unique identifier of the option, persistent on option addition and deletion |
| text | String | Yes | Option text, 1-100 characters |
| text_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the option text. Currently, only custom emoji entities are allowed in poll option texts |
| voter_count | Integer | Yes | Number of users who voted for this option; may be 0 if unknown |
| added_by_user | User | Optional | Optional. User who added the option; omitted if the option wasn't added by a user after poll creation |
| added_by_chat | Chat | Optional | Optional. Chat that added the option; omitted if the option wasn't added by a chat after poll creation |
| addition_date | Integer | Optional | Optional. Point in time (Unix timestamp) when the option was added; omitted if the option existed in the original poll |
