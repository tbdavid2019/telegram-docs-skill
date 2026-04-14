# Type: InputContactMessageContent

**Category**: Inline mode

**Description**: Represents the content of a contact message to be sent as the result of an inline query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputcontactmessagecontent)

**Subtype of**: InputMessageContent

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| phone_number | String | Yes | Contact's phone number |
| first_name | String | Yes | Contact's first name |
| last_name | String | Optional | Optional. Contact's last name |
| vcard | String | Optional | Optional. Additional data about the contact in the form of a vCard, 0-2048 bytes |
