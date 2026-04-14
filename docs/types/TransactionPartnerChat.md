# Type: TransactionPartnerChat

**Category**: Payments

**Description**: Describes a transaction with a chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#transactionpartnerchat)

**Subtype of**: TransactionPartner

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the transaction partner, always "chat" |
| chat | Chat | Yes | Information about the chat |
| gift | Gift | Optional | Optional. The gift sent to the chat by the bot |
