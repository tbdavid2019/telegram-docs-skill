# Type: Invoice

**Category**: Payments

**Description**: This object contains basic information about an invoice.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#invoice)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| title | String | Yes | Product name |
| description | String | Yes | Product description |
| start_parameter | String | Yes | Unique bot deep-linking parameter that can be used to generate this invoice |
| currency | String | Yes | Three-letter ISO 4217 currency code, or "XTR" for payments in Telegram Stars |
| total_amount | Integer | Yes | Total price in the smallest units of the currency (integer, not float/double). For example, for a price of US$ 1.45 pass amount = 145. See the exp parameter in currencies.json, it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). |
