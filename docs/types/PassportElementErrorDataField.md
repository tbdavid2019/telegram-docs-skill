# Type: PassportElementErrorDataField

**Category**: Telegram Passport

**Description**: Represents an issue in one of the data fields that was provided by the user. The error is considered resolved when the field's value changes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrordatafield)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be data |
| type | String | Yes | The section of the user's Telegram Passport which has the error, one of "personal_details", "passport", "driver_license", "identity_card", "internal_passport", "address" |
| field_name | String | Yes | Name of the data field which has the error |
| data_hash | String | Yes | Base64-encoded data hash |
| message | String | Yes | Error message |
