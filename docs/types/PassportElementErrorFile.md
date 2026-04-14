# Type: PassportElementErrorFile

**Category**: Telegram Passport

**Description**: Represents an issue with a document scan. The error is considered resolved when the file with the document scan changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrorfile)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be file |
| type | String | Yes | The section of the user's Telegram Passport which has the issue, one of "utility_bill", "bank_statement", "rental_agreement", "passport_registration", "temporary_registration" |
| file_hash | String | Yes | Base64-encoded file hash |
| message | String | Yes | Error message |
