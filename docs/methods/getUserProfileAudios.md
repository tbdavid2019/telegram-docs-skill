# Method: getUserProfileAudios

**Category**: Available methods

**Description**: Use this method to get a list of profile audios for a user. Returns a UserProfileAudios object.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getuserprofileaudios)

**Returns**: UserProfileAudios

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| user_id | Integer | Yes | Unique identifier of the target user |
| offset | Integer | Optional | Sequential number of the first audio to be returned. By default, all audios are returned. |
| limit | Integer | Optional | Limits the number of audios to be retrieved. Values between 1-100 are accepted. Defaults to 100. |
