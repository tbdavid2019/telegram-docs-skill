# Type: RefundedPayment

**Category**: Payments

**Description**: This object contains basic information about a refunded payment.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#refundedpayment)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| currency | String | Yes | Three-letter ISO 4217 currency code, or "XTR" for payments in Telegram Stars. Currently, always "XTR" |
| total_amount | Integer | Yes | Total refunded price in the smallest units of the currency (integer, not float/double). For example, for a price of US$ 1.45, total_amount = 145. See the exp parameter in currencies.json, it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). |
| invoice_payload | String | Yes | Bot-specified invoice payload |
| telegram_payment_charge_id | String | Yes | Telegram payment identifier |
| provider_payment_charge_id | String | Optional | Optional. Provider payment identifier |
