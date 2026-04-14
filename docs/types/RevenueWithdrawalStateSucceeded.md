# Type: RevenueWithdrawalStateSucceeded

**Category**: Payments

**Description**: The withdrawal succeeded.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#revenuewithdrawalstatesucceeded)

**Subtype of**: RevenueWithdrawalState

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the state, always "succeeded" |
| date | Integer | Yes | Date the withdrawal was completed in Unix time |
| url | String | Yes | An HTTPS URL that can be used to see transaction details |
