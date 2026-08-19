# Type: BotSubscriptionUpdated

**Category**: Available types

**Description**: This object contains information about changes to a user payment subscription toward the current bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#botsubscriptionupdated)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| user | User | Yes | User who subscribed for payments toward the bot |
| invoice_payload | String | Yes | Bot-specified invoice payload |
| state | String | Yes | The new state of the subscription. Currently, it can be one of "canceled" if the user canceled the subscription, "active" if the user re-enabled a previously canceled subscription, or "failed" if payment for the subscription failed. |
