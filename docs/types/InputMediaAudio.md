# Type: InputMediaAudio

**Category**: Available types

**Description**: Represents an audio file to be treated as music to be sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputmediaaudio)

**Subtype of**: InputMedia

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the result, must be audio |
| media | String | Yes | File to send. Pass a file_id to send a file that exists on the Telegram servers (recommended), pass an HTTP URL for Telegram to get a file from the Internet, or pass "attach://<file_attach_name>" to upload a new one using multipart/form-data under <file_attach_name> name. More information on Sending Files: https://core.telegram.org/bots/api#sending-files |
| thumbnail | String | Optional | Optional. Thumbnail of the file sent; can be ignored if thumbnail generation for the file is supported server-side. The thumbnail should be in JPEG format and less than 200 kB in size. A thumbnail's width and height should not exceed 320. Ignored if the file is not uploaded using multipart/form-data. Thumbnails can't be reused and can be only uploaded as a new file, so you can pass "attach://<file_attach_name>" if the thumbnail was uploaded using multipart/form-data under <file_attach_name>. More information on Sending Files: https://core.telegram.org/bots/api#sending-files |
| caption | String | Optional | Optional. Caption of the audio to be sent, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the audio caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| duration | Integer | Optional | Optional. Duration of the audio in seconds |
| performer | String | Optional | Optional. Performer of the audio |
| title | String | Optional | Optional. Title of the audio |
