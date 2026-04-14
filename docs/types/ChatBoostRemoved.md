# Type: ChatBoostRemoved

**Category**: Available types

**Description**: This object represents a boost removed from a chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatboostremoved)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| chat | Chat | Yes | Chat which was boosted |
| boost_id | String | Yes | Unique identifier of the boost |
| remove_date | Integer | Yes | Point in time (Unix timestamp) when the boost was removed |
| source | ChatBoostSource | Yes | Source of the removed boost |
