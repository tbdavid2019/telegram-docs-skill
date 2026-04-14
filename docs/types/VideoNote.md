# Type: VideoNote

**Category**: Available types

**Description**: This object represents a video message (available in Telegram apps as of v.4.0).

**Link**: [Official Documentation](https://core.telegram.org/bots/api#videonote)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| file_id | String | Yes | Identifier for this file, which can be used to download or reuse the file |
| file_unique_id | String | Yes | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can't be used to download or reuse the file. |
| length | Integer | Yes | Video width and height (diameter of the video message) as defined by the sender |
| duration | Integer | Yes | Duration of the video in seconds as defined by the sender |
| thumbnail | PhotoSize | Optional | Optional. Video thumbnail |
| file_size | Integer | Optional | Optional. File size in bytes |
