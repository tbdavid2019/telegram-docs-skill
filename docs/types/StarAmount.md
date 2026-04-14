# Type: StarAmount

**Category**: Available types

**Description**: Describes an amount of Telegram Stars.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#staramount)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| amount | Integer | Yes | Integer amount of Telegram Stars, rounded to 0; can be negative |
| nanostar_amount | Integer | Optional | Optional. The number of 1/1000000000 shares of Telegram Stars; from -999999999 to 999999999; can be negative if and only if amount is non-positive |
