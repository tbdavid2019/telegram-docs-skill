# Type: TransactionPartnerAffiliateProgram

**Category**: Payments

**Description**: Describes the affiliate program that issued the affiliate commission received via this transaction.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#transactionpartneraffiliateprogram)

**Subtype of**: TransactionPartner

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the transaction partner, always "affiliate_program" |
| sponsor_user | User | Optional | Optional. Information about the bot that sponsored the affiliate program |
| commission_per_mille | Integer | Yes | The number of Telegram Stars received by the bot for each 1000 Telegram Stars received by the affiliate program sponsor from referred users |
