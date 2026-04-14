# Method: transferBusinessAccountStars

**Category**: Available methods

**Description**: Transfers Telegram Stars from the business account balance to the bot's balance. Requires the can_transfer_stars business bot right. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#transferbusinessaccountstars)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection |
| star_count | Integer | Yes | Number of Telegram Stars to transfer; 1-10000 |
