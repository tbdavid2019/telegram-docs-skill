# Type: EncryptedCredentials

**Category**: Telegram Passport

**Description**: Describes data required for decrypting and authenticating EncryptedPassportElement. See the Telegram Passport Documentation for a complete description of the data decryption and authentication processes.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#encryptedcredentials)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| data | String | Yes | Base64-encoded encrypted JSON-serialized data with unique user's payload, data hashes and secrets required for EncryptedPassportElement decryption and authentication |
| hash | String | Yes | Base64-encoded data hash for data authentication |
| secret | String | Yes | Base64-encoded secret, encrypted with the bot's public RSA key, required for data decryption |
