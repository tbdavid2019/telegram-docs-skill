# Type: InputProfilePhotoStatic

**Category**: Available types

**Description**: A static profile photo in the .JPG format.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputprofilephotostatic)

**Subtype of**: InputProfilePhoto

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the profile photo, must be static |
| photo | String | Yes | The static profile photo. Profile photos can't be reused and can only be uploaded as a new file, so you can pass "attach://<file_attach_name>" if the photo was uploaded using multipart/form-data under <file_attach_name>. More information on Sending Files: https://core.telegram.org/bots/api#sending-files |
