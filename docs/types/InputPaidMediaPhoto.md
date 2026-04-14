# Type: InputPaidMediaPhoto

**Category**: Available types

**Description**: The paid media to send is a photo.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputpaidmediaphoto)

**Subtype of**: InputPaidMedia

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the media, must be photo |
| media | String | Yes | File to send. Pass a file_id to send a file that exists on the Telegram servers (recommended), pass an HTTP URL for Telegram to get a file from the Internet, or pass "attach://<file_attach_name>" to upload a new one using multipart/form-data under <file_attach_name> name. More information on Sending Files: https://core.telegram.org/bots/api#sending-files |
