# Type: PassportElementErrorUnspecified

**Category**: Telegram Passport

**Description**: Represents an issue in an unspecified place. The error is considered resolved when new data is added.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportelementerrorunspecified)

**Subtype of**: PassportElementError

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| source | String | Yes | Error source, must be unspecified |
| type | String | Yes | Type of element of the user's Telegram Passport which has the issue |
| element_hash | String | Yes | Base64-encoded element hash |
| message | String | Yes | Error message |
