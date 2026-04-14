# Type: InlineQueryResultContact

**Category**: Inline mode

**Description**: Represents a contact with a phone number. By default, this contact will be sent by the user. Alternatively, you can use input_message_content to send a message with the specified content instead of the contact.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inlinequeryresultcontact)

**Subtype of**: InlineQueryResult

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be contact |
| id | String | Yes | Unique identifier for this result, 1-64 Bytes |
| phone_number | String | Yes | Contact's phone number |
| first_name | String | Yes | Contact's first name |
| last_name | String | Optional | Optional. Contact's last name |
| vcard | String | Optional | Optional. Additional data about the contact in the form of a vCard, 0-2048 bytes |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message |
| input_message_content | InputMessageContent | Optional | Optional. Content of the message to be sent instead of the contact |
| thumbnail_url | String | Optional | Optional. Url of the thumbnail for the result |
| thumbnail_width | Integer | Optional | Optional. Thumbnail width |
| thumbnail_height | Integer | Optional | Optional. Thumbnail height |
