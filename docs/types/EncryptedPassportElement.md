# Type: EncryptedPassportElement

**Category**: Telegram Passport

**Description**: Describes documents or other Telegram Passport elements shared with the bot by the user.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#encryptedpassportelement)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Element type. One of "personal_details", "passport", "driver_license", "identity_card", "internal_passport", "address", "utility_bill", "bank_statement", "rental_agreement", "passport_registration", "temporary_registration", "phone_number", "email". |
| data | String | Optional | Optional. Base64-encoded encrypted Telegram Passport element data provided by the user; available only for "personal_details", "passport", "driver_license", "identity_card", "internal_passport" and "address" types. Can be decrypted and verified using the accompanying EncryptedCredentials. |
| phone_number | String | Optional | Optional. User's verified phone number; available only for "phone_number" type |
| email | String | Optional | Optional. User's verified email address; available only for "email" type |
| files | Array of PassportFile | Optional | Optional. Array of encrypted files with documents provided by the user; available only for "utility_bill", "bank_statement", "rental_agreement", "passport_registration" and "temporary_registration" types. Files can be decrypted and verified using the accompanying EncryptedCredentials. |
| front_side | PassportFile | Optional | Optional. Encrypted file with the front side of the document, provided by the user; available only for "passport", "driver_license", "identity_card" and "internal_passport". The file can be decrypted and verified using the accompanying EncryptedCredentials. |
| reverse_side | PassportFile | Optional | Optional. Encrypted file with the reverse side of the document, provided by the user; available only for "driver_license" and "identity_card". The file can be decrypted and verified using the accompanying EncryptedCredentials. |
| selfie | PassportFile | Optional | Optional. Encrypted file with the selfie of the user holding a document, provided by the user; available if requested for "passport", "driver_license", "identity_card" and "internal_passport". The file can be decrypted and verified using the accompanying EncryptedCredentials. |
| translation | Array of PassportFile | Optional | Optional. Array of encrypted files with translated versions of documents provided by the user; available if requested for "passport", "driver_license", "identity_card", "internal_passport", "utility_bill", "bank_statement", "rental_agreement", "passport_registration" and "temporary_registration" types. Files can be decrypted and verified using the accompanying EncryptedCredentials. |
| hash | String | Yes | Base64-encoded element hash for using in PassportElementErrorUnspecified |
