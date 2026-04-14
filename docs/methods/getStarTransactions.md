# Method: getStarTransactions

**Category**: Payments

**Description**: Returns the bot's Telegram Star transactions in chronological order. On success, returns a StarTransactions object.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getstartransactions)

**Returns**: StarTransactions

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| offset | Integer | Optional | Number of transactions to skip in the response |
| limit | Integer | Optional | The maximum number of transactions to be retrieved. Values between 1-100 are accepted. Defaults to 100. |
