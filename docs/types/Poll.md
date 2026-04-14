# Type: Poll

**Category**: Available types

**Description**: This object contains information about a poll.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#poll)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique poll identifier |
| question | String | Yes | Poll question, 1-300 characters |
| question_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the question. Currently, only custom emoji entities are allowed in poll questions |
| options | Array of PollOption | Yes | List of poll options |
| total_voter_count | Integer | Yes | Total number of users that voted in the poll |
| is_closed | Boolean | Yes | True, if the poll is closed |
| is_anonymous | Boolean | Yes | True, if the poll is anonymous |
| type | String | Yes | Poll type, currently can be "regular" or "quiz" |
| allows_multiple_answers | Boolean | Yes | True, if the poll allows multiple answers |
| allows_revoting | Boolean | Yes | True, if the poll allows to change the chosen answer options |
| correct_option_ids | Array of Integer | Optional | Optional. Array of 0-based identifiers of the correct answer options. Available only for polls in quiz mode which are closed or were sent (not forwarded) by the bot or to the private chat with the bot. |
| explanation | String | Optional | Optional. Text that is shown when a user chooses an incorrect answer or taps on the lamp icon in a quiz-style poll, 0-200 characters |
| explanation_entities | Array of MessageEntity | Optional | Optional. Special entities like usernames, URLs, bot commands, etc. that appear in the explanation |
| open_period | Integer | Optional | Optional. Amount of time in seconds the poll will be active after creation |
| close_date | Integer | Optional | Optional. Point in time (Unix timestamp) when the poll will be automatically closed |
| description | String | Optional | Optional. Description of the poll; for polls inside the Message object only |
| description_entities | Array of MessageEntity | Optional | Optional. Special entities like usernames, URLs, bot commands, etc. that appear in the description |
