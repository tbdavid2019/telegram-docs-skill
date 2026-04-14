# Type: ChatBoost

**Category**: Available types

**Description**: This object contains information about a chat boost.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatboost)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| boost_id | String | Yes | Unique identifier of the boost |
| add_date | Integer | Yes | Point in time (Unix timestamp) when the chat was boosted |
| expiration_date | Integer | Yes | Point in time (Unix timestamp) when the boost will automatically expire, unless the booster's Telegram Premium subscription is prolonged |
| source | ChatBoostSource | Yes | Source of the added boost |
