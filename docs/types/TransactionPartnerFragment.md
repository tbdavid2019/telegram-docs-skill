# Type: TransactionPartnerFragment

**Category**: Payments

**Description**: Describes a withdrawal transaction with Fragment.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#transactionpartnerfragment)

**Subtype of**: TransactionPartner

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the transaction partner, always "fragment" |
| withdrawal_state | RevenueWithdrawalState | Optional | Optional. State of the transaction if the transaction is outgoing |
