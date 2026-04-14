# Type: InputChecklistTask

**Category**: Available types

**Description**: Describes a task to add to a checklist.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputchecklisttask)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | Integer | Yes | Unique identifier of the task; must be positive and unique among all task identifiers currently present in the checklist |
| text | String | Yes | Text of the task; 1-100 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the text. See formatting options for more details. |
| text_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the text, which can be specified instead of parse_mode. Currently, only bold, italic, underline, strikethrough, spoiler, custom_emoji, and date_time entities are allowed. |
