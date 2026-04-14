# Type: InputMediaPhoto

**Category**: Available types

**Description**: Represents a photo to be sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputmediaphoto)

**Subtype of**: InputMedia

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be photo |
| media | String | Yes | File to send. Pass a file_id to send a file that exists on the Telegram servers (recommended), pass an HTTP URL for Telegram to get a file from the Internet, or pass "attach://<file_attach_name>" to upload a new one using multipart/form-data under <file_attach_name> name. More information on Sending Files: https://core.telegram.org/bots/api#sending-files |
| caption | String | Optional | Optional. Caption of the photo to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the photo caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| show_caption_above_media | Boolean | Optional | Optional. Pass True, if the caption must be shown above the message media |
| has_spoiler | Boolean | Optional | Optional. Pass True if the photo needs to be covered with a spoiler animation |
