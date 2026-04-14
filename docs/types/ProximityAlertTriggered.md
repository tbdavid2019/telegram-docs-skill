# Type: ProximityAlertTriggered

**Category**: Available types

**Description**: This object represents the content of a service message, sent whenever a user in the chat triggers a proximity alert set by another user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#proximityalerttriggered)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| traveler | User | Yes | User that triggered the alert |
| watcher | User | Yes | User that set the alert |
| distance | Integer | Yes | The distance between the users |
