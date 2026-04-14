# Method: setBusinessAccountUsername

**Category**: Available methods

**Description**: Changes the username of a managed business account. Requires the can_change_username business bot right. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setbusinessaccountusername)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection |
| username | String | Optional | The new value of the username for the business account; 0-32 characters |
