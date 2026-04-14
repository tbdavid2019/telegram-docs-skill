# Type: SuggestedPostApproved

**Category**: Available types

**Description**: Describes a service message about the approval of a suggested post.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#suggestedpostapproved)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| suggested_post_message | Message | Optional | Optional. Message containing the suggested post. Note that the Message object in this field will not contain the reply_to_message field even if it itself is a reply. |
| price | SuggestedPostPrice | Optional | Optional. Amount paid for the post |
| send_date | Integer | Yes | Date when the post will be published |
