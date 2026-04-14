# Type: Checklist

**Category**: Available types

**Description**: Describes a checklist.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#checklist)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| title | String | Yes | Title of the checklist |
| title_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the checklist title |
| tasks | Array of ChecklistTask | Yes | List of tasks in the checklist |
| others_can_add_tasks | Boolean | Optional | Optional. True, if users other than the creator of the list can add tasks to the list |
| others_can_mark_tasks_as_done | Boolean | Optional | Optional. True, if users other than the creator of the list can mark tasks as done or not done |
