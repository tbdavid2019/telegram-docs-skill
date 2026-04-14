# Type: GiveawayCompleted

**Category**: Available types

**Description**: This object represents a service message about the completion of a giveaway without public winners.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#giveawaycompleted)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| winner_count | Integer | Yes | Number of winners in the giveaway |
| unclaimed_prize_count | Integer | Optional | Optional. Number of undistributed prizes |
| giveaway_message | Message | Optional | Optional. Message with the giveaway that was completed, if it wasn't deleted |
| is_star_giveaway | Boolean | Optional | Optional. True, if the giveaway is a Telegram Star giveaway. Otherwise, currently, the giveaway is a Telegram Premium giveaway. |
