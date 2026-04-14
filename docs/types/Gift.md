# Type: Gift

**Category**: Available types

**Description**: This object represents a gift that can be sent by the bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#gift)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique identifier of the gift |
| sticker | Sticker | Yes | The sticker that represents the gift |
| star_count | Integer | Yes | The number of Telegram Stars that must be paid to send the sticker |
| upgrade_star_count | Integer | Optional | Optional. The number of Telegram Stars that must be paid to upgrade the gift to a unique one |
| is_premium | Boolean | Optional | Optional. True, if the gift can only be purchased by Telegram Premium subscribers |
| has_colors | Boolean | Optional | Optional. True, if the gift can be used (after being upgraded) to customize a user's appearance |
| total_count | Integer | Optional | Optional. The total number of gifts of this type that can be sent by all users; for limited gifts only |
| remaining_count | Integer | Optional | Optional. The number of remaining gifts of this type that can be sent by all users; for limited gifts only |
| personal_total_count | Integer | Optional | Optional. The total number of gifts of this type that can be sent by the bot; for limited gifts only |
| personal_remaining_count | Integer | Optional | Optional. The number of remaining gifts of this type that can be sent by the bot; for limited gifts only |
| background | GiftBackground | Optional | Optional. Background of the gift |
| unique_gift_variant_count | Integer | Optional | Optional. The total number of different unique gifts that can be obtained by upgrading the gift |
| publisher_chat | Chat | Optional | Optional. Information about the chat that published the gift |
