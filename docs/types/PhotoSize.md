# Type: PhotoSize

**Category**: Available types

**Description**: This object represents one size of a photo or a file / sticker thumbnail.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#photosize)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| file_id | String | Yes | Identifier for this file, which can be used to download or reuse the file |
| file_unique_id | String | Yes | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can't be used to download or reuse the file. |
| width | Integer | Yes | Photo width |
| height | Integer | Yes | Photo height |
| file_size | Integer | Optional | Optional. File size in bytes |
