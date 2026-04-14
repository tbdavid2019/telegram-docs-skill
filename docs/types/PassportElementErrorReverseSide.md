# Type: PassportElementErrorReverseSide

**Category**: Telegram Passport

**Description**: Represents an issue with the reverse side of a document. The error is considered resolved when the file with reverse side of the document changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrorreverseside)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be reverse_side |
| type | String | Yes | The section of the user's Telegram Passport which has the issue, one of "driver_license", "identity_card" |
| file_hash | String | Yes | Base64-encoded hash of the file with the reverse side of the document |
| message | String | Yes | Error message |
