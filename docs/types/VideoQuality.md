# Type: VideoQuality

**Category**: Available types

**Description**: This object represents a video file of a specific quality.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#videoquality)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| file_id | String | Yes | Identifier for this file, which can be used to download or reuse the file |
| file_unique_id | String | Yes | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can't be used to download or reuse the file. |
| width | Integer | Yes | Video width |
| height | Integer | Yes | Video height |
| codec | String | Yes | Codec that was used to encode the video, for example, "h264", "h265", or "av01" |
| file_size | Integer | Optional | Optional. File size in bytes. It can be bigger than 2^31 and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this value. |
