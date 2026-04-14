# Type: SuggestedPostPaid

**Category**: Available types

**Description**: Describes a service message about a successful payment for a suggested post.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#suggestedpostpaid)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| suggested_post_message | Message | Optional | Optional. Message containing the suggested post. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| currency | String | Yes | Currency in which the payment was made. Currently, one of "XTR" for Telegram Stars or "TON" for toncoins |
| amount | Integer | Optional | Optional. The amount of the currency that was received by the channel in nanotoncoins; for payments in toncoins only |
| star_amount | StarAmount | Optional | Optional. The amount of Telegram Stars that was received by the channel; for payments in Telegram Stars only |
