# Type: PreCheckoutQuery

**Category**: Payments

**Description**: This object contains information about an incoming pre-checkout query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#precheckoutquery)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique query identifier |
| from | User | Yes | User who sent the query |
| currency | String | Yes | Three-letter ISO 4217 currency code, or "XTR" for payments in Telegram Stars |
| total_amount | Integer | Yes | Total price in the smallest units of the currency (integer, not float/double). For example, for a price of US$ 1.45 pass amount = 145. See the exp parameter in currencies.json, it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). |
| invoice_payload | String | Yes | Bot-specified invoice payload |
| shipping_option_id | String | Optional | Optional. Identifier of the shipping option chosen by the user |
| order_info | OrderInfo | Optional | Optional. Order information provided by the user |
