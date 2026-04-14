# Method: verifyUser

**Category**: Available methods

**Description**: Verifies a user on behalf of the organization which is represented by the bot. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#verifyuser)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| user_id | Integer | Yes | Unique identifier of the target user |
| custom_description | String | Optional | Custom description for the verification; 0-70 characters. Must be empty if the organization isn't allowed to provide a custom verification description. |
