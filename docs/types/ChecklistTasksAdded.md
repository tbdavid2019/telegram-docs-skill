# Type: ChecklistTasksAdded

**Category**: Available types

**Description**: Describes a service message about tasks added to a checklist.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#checklisttasksadded)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| checklist_message | Message | Optional | Optional. Message containing the checklist to which the tasks were added. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| tasks | Array of ChecklistTask | Yes | List of tasks added to the checklist |
