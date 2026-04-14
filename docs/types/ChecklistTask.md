# Type: ChecklistTask

**Category**: Available types

**Description**: Describes a task in a checklist.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#checklisttask)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | Integer | Yes | Unique identifier of the task |
| text | String | Yes | Text of the task |
| text_entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the task text |
| completed_by_user | User | Optional | Optional. User that completed the task; omitted if the task wasn't completed by a user |
| completed_by_chat | Chat | Optional | Optional. Chat that completed the task; omitted if the task wasn't completed by a chat |
| completion_date | Integer | Optional | Optional. Point in time (Unix timestamp) when the task was completed; 0 if the task wasn't completed |
