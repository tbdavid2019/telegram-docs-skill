# Type: ChatBoostSourceGiftCode

**Category**: Available types

**Description**: The boost was obtained by the creation of Telegram Premium gift codes to boost a chat. Each such code boosts the chat 4 times for the duration of the corresponding Telegram Premium subscription.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatboostsourcegiftcode)

**Subtype of**: ChatBoostSource

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Source of the boost, always "gift_code" |
| user | User | Yes | User for which the gift code was created |
