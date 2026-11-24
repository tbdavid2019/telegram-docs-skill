# Type: PassportData

**Category**: Telegram Passport

**Description**: Describes Telegram Passport data shared with the bot by the user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#passportdata)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| data | Array of EncryptedPassportElement | Yes | Array with information shared with the bot about documents and other Telegram Passport elements |
| credentials | EncryptedCredentials | Yes | Encrypted credentials required to decrypt the data |
