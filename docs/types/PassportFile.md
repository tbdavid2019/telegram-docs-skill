# Type: PassportFile

**Category**: Telegram Passport

**Description**: This object represents a file uploaded to Telegram Passport. Currently all Telegram Passport files are in JPEG format when decrypted and don't exceed 10MB.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportfile)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| file_id | String | Yes | Identifier for this file, which can be used to download or reuse the file |
| file_unique_id | String | Yes | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can't be used to download or reuse the file. |
| file_size | Integer | Yes | File size in bytes |
| file_date | Integer | Yes | Unix time when the file was uploaded |
