# Type: PassportElementErrorFiles

**Category**: Telegram Passport

**Description**: Represents an issue with a list of scans. The error is considered resolved when the list of files containing the scans changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrorfiles)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be files |
| type | String | Yes | The section of the user's Telegram Passport which has the issue, one of "utility_bill", "bank_statement", "rental_agreement", "passport_registration", "temporary_registration" |
| file_hashes | Array of String | Yes | List of base64-encoded file hashes |
| message | String | Yes | Error message |
