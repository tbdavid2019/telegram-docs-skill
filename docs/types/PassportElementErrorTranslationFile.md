# Type: PassportElementErrorTranslationFile

**Category**: Telegram Passport

**Description**: Represents an issue with one of the files that constitute the translation of a document. The error is considered resolved when the file changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrortranslationfile)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be translation_file |
| type | String | Yes | Type of element of the user's Telegram Passport which has the issue, one of "passport", "driver_license", "identity_card", "internal_passport", "utility_bill", "bank_statement", "rental_agreement", "passport_registration", "temporary_registration" |
| file_hash | String | Yes | Base64-encoded file hash |
| message | String | Yes | Error message |
