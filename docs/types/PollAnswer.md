# Type: PollAnswer

**Category**: Available types

**Description**: This object represents an answer of a user in a non-anonymous poll.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#pollanswer)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| poll_id | String | Yes | Unique poll identifier |
| voter_chat | Chat | Optional | Optional. The chat that changed the answer to the poll, if the voter is anonymous |
| user | User | Optional | Optional. The user that changed the answer to the poll, if the voter isn't anonymous |
| option_ids | Array of Integer | Yes | 0-based identifiers of chosen answer options. May be empty if the vote was retracted. |
| option_persistent_ids | Array of String | Yes | Persistent identifiers of the chosen answer options. May be empty if the vote was retracted. |
