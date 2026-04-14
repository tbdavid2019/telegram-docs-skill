# Type: PassportElementErrorTranslationFiles

**Category**: Telegram Passport

**Description**: Represents an issue with the translated version of a document. The error is considered resolved when a file with the document translation change.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrortranslationfiles)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be translation_files |
| type | String | Yes | Type of element of the user's Telegram Passport which has the issue, one of "passport", "driver_license", "identity_card", "internal_passport", "utility_bill", "bank_statement", "rental_agreement", "passport_registration", "temporary_registration" |
| file_hashes | Array of String | Yes | List of base64-encoded file hashes |
| message | String | Yes | Error message |
