# Type: LivePhoto

**Category**: Available types

**Description**: This object represents a live photo.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#livephoto)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| photo | Array of PhotoSize | Optional | Optional. Available sizes of the corresponding static photo |
| file_id | String | Yes | Identifier for the video file which can be used to download or reuse the file |
| file_unique_id | String | Yes | Unique identifier for the video file which is supposed to be the same over time and for different bots. Can't be used to download or reuse the file. |
| width | Integer | Yes | Video width as defined by the sender |
| height | Integer | Yes | Video height as defined by the sender |
| duration | Integer | Yes | Duration of the video in seconds as defined by the sender |
| mime_type | String | Optional | Optional. MIME type of the file as defined by the sender |
| file_size | Integer | Optional | Optional. File size in bytes. It can be bigger than 2^31 and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this value. |
