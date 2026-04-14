# Type: AffiliateInfo

**Category**: Payments

**Description**: Contains information about the affiliate that received a commission via this transaction.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#affiliateinfo)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| affiliate_user | User | Optional | Optional. The bot or the user that received an affiliate commission if it was received by a bot or a user |
| affiliate_chat | Chat | Optional | Optional. The chat that received an affiliate commission if it was received by a chat |
| commission_per_mille | Integer | Yes | The number of Telegram Stars received by the affiliate for each 1000 Telegram Stars received by the bot from referred users |
| amount | Integer | Yes | Integer amount of Telegram Stars received by the affiliate from the transaction, rounded to 0; can be negative for refunds |
| nanostar_amount | Integer | Optional | Optional. The number of 1/1000000000 shares of Telegram Stars received by the affiliate; from -999999999 to 999999999; can be negative for refunds |
