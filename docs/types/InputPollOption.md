# Type: InputPollOption

**Category**: Available types

**Description**: This object contains information about one answer option in a poll to be sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputpolloption)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| text | String | Yes | Option text, 1-100 characters |
| text_parse_mode | String | Optional | Optional. Mode for parsing entities in the text. See formatting options for more details. Currently, only custom emoji entities are allowed |
| text_entities | Array of MessageEntity | Optional | Optional. A JSON-serialized list of special entities that appear in the poll option text. It can be specified instead of text_parse_mode |
