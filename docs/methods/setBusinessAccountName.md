# Method: setBusinessAccountName

**Category**: Available methods

**Description**: Changes the first and last name of a managed business account. Requires the can_change_name business bot right. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setbusinessaccountname)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection |
| first_name | String | Yes | The new value of the first name for the business account; 1-64 characters |
| last_name | String | Optional | The new value of the last name for the business account; 0-64 characters |
