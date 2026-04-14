# Type: SuggestedPostDeclined

**Category**: Available types

**Description**: Describes a service message about the rejection of a suggested post.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#suggestedpostdeclined)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| suggested_post_message | Message | Optional | Optional. Message containing the suggested post. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| comment | String | Optional | Optional. Comment with which the post was declined |
