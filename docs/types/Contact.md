# Type: Contact

**Category**: Available types

**Description**: This object represents a phone contact.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#contact)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| phone_number | String | Yes | Contact's phone number |
| first_name | String | Yes | Contact's first name |
| last_name | String | Optional | Optional. Contact's last name |
| user_id | Integer | Optional | Optional. Contact's user identifier in Telegram. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. |
| vcard | String | Optional | Optional. Additional data about the contact in the form of a vCard |
