# Type: PassportElementErrorSelfie

**Category**: Telegram Passport

**Description**: Represents an issue with the selfie with a document. The error is considered resolved when the file with the selfie changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrorselfie)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be selfie |
| type | String | Yes | The section of the user's Telegram Passport which has the issue, one of "passport", "driver_license", "identity_card", "internal_passport" |
| file_hash | String | Yes | Base64-encoded hash of the file with the selfie |
| message | String | Yes | Error message |
