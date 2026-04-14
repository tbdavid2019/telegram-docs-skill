# Method: convertGiftToStars

**Category**: Available methods

**Description**: Converts a given regular gift to Telegram Stars. Requires the can_convert_gifts_to_stars business bot right. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#convertgifttostars)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection |
| owned_gift_id | String | Yes | Unique identifier of the regular gift that should be converted to Telegram Stars |
