# Type: ChecklistTasksDone

**Category**: Available types

**Description**: Describes a service message about checklist tasks marked as done or not done.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#checklisttasksdone)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| checklist_message | Message | Optional | Optional. Message containing the checklist whose tasks were marked as done or not done. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| marked_as_done_task_ids | Array of Integer | Optional | Optional. Identifiers of the tasks that were marked as done |
| marked_as_not_done_task_ids | Array of Integer | Optional | Optional. Identifiers of the tasks that were marked as not done |
