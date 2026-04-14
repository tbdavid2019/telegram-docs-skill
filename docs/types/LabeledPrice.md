# Type: LabeledPrice

**Category**: Payments

**Description**: This object represents a portion of the price for goods or services.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#labeledprice)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| label | String | Yes | Portion label |
| amount | Integer | Yes | Price of the product in the smallest units of the currency (integer, not float/double). For example, for a price of US$ 1.45 pass amount = 145. See the exp parameter in currencies.json, it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). |
