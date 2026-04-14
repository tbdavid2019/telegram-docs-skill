# Type: KeyboardButtonRequestManagedBot

**Category**: Available types

**Description**: This object defines the parameters for the creation of a managed bot. Information about the created bot will be shared with the bot using the update managed_bot and a Message with the field managed_bot_created.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#keyboardbuttonrequestmanagedbot)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| request_id | Integer | Yes | Signed 32-bit identifier of the request. Must be unique within the message |
| suggested_name | String | Optional | Optional. Suggested name for the bot |
| suggested_username | String | Optional | Optional. Suggested username for the bot |
