# Type: Giveaway

**Category**: Available types

**Description**: This object represents a message about a scheduled giveaway.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#giveaway)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| chats | Array of Chat | Yes | The list of chats which the user must join to participate in the giveaway |
| winners_selection_date | Integer | Yes | Point in time (Unix timestamp) when winners of the giveaway will be selected |
| winner_count | Integer | Yes | The number of users which are supposed to be selected as winners of the giveaway |
| only_new_members | Boolean | Optional | Optional. True, if only users who join the chats after the giveaway started should be eligible to win |
| has_public_winners | Boolean | Optional | Optional. True, if the list of giveaway winners will be visible to everyone |
| prize_description | String | Optional | Optional. Description of additional giveaway prize |
| country_codes | Array of String | Optional | Optional. A list of two-letter ISO 3166-1 alpha-2 country codes indicating the countries from which eligible users for the giveaway must come. If empty, then all users can participate in the giveaway. Users with a phone number that was bought on Fragment can always participate in giveaways. |
| prize_star_count | Integer | Optional | Optional. The number of Telegram Stars to be split between giveaway winners; for Telegram Star giveaways only |
| premium_subscription_month_count | Integer | Optional | Optional. The number of months the Telegram Premium subscription won from the giveaway will be active for; for Telegram Premium giveaways only |
