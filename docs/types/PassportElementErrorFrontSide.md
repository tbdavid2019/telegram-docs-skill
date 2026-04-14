# Type: PassportElementErrorFrontSide

**Category**: Telegram Passport

**Description**: Represents an issue with the front side of a document. The error is considered resolved when the file with the front side of the document changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrorfrontside)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be front_side |
| type | String | Yes | The section of the user's Telegram Passport which has the issue, one of "passport", "driver_license", "identity_card", "internal_passport" |
| file_hash | String | Yes | Base64-encoded hash of the file with the front side of the document |
| message | String | Yes | Error message |
