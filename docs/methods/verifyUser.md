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
| custom_description_parse_mode | String | Optional | Mode for parsing entities in the custom description. See formatting options for more details. Only "text_link" entities are supported. |
| custom_description_entities | Array of MessageEntity | Optional | A JSON-serialized list of special entities that appear in the custom description, which can be specified instead of custom_description_parse_mode. Only "text_link" entities are supported. |
