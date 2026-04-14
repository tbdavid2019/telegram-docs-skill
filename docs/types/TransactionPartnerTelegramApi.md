# Type: TransactionPartnerTelegramApi

**Category**: Payments

**Description**: Describes a transaction with payment for paid broadcasting.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#transactionpartnertelegramapi)

**Subtype of**: TransactionPartner

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the transaction partner, always "telegram_api" |
| request_count | Integer | Yes | The number of successful requests that exceeded regular limits and were therefore billed |
