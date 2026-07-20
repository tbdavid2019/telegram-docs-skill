# Type: InputPaidMediaLivePhoto

**Category**: Available types

**Description**: The paid media to send is a live photo.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputpaidmedialivephoto)

**Subtype of**: InputPaidMedia

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the media, must be live_photo |
| media | String | Yes | Video of the live photo to send. Pass a file_id to send a file that exists on the Telegram servers (recommended) or pass "attach://<file_attach_name>" to upload a new one using multipart/form-data under <file_attach_name> name. More information on Sending Files: https://core.telegram.org/bots/api#sending-files. Sending live photos by a URL is currently unsupported. |
| photo | String | Yes | The static photo to send. Pass a file_id to send a file that exists on the Telegram servers (recommended) or pass "attach://<file_attach_name>" to upload a new one using multipart/form-data under <file_attach_name> name. More information on Sending Files: https://core.telegram.org/bots/api#sending-files. Sending live photos by a URL is currently unsupported. |
