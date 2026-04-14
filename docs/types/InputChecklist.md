# Type: InputChecklist

**Category**: Available types

**Description**: Describes a checklist to create.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputchecklist)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| title | String | Yes | Title of the checklist; 1-255 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the title. See formatting options for more details. |
| title_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the title, which can be specified instead of parse_mode. Currently, only bold, italic, underline, strikethrough, spoiler, custom_emoji, and date_time entities are allowed. |
| tasks | Array of InputChecklistTask | Yes | List of 1-30 tasks in the checklist |
| others_can_add_tasks | Boolean | Optional | Optional. Pass True if other users can add tasks to the checklist |
| others_can_mark_tasks_as_done | Boolean | Optional | Optional. Pass True if other users can mark tasks as done or not done in the checklist |
