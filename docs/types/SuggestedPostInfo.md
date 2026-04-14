# Type: SuggestedPostInfo

**Category**: Available types

**Description**: Contains information about a suggested post.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#suggestedpostinfo)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| state | String | Yes | State of the suggested post. Currently, it can be one of "pending", "approved", "declined". |
| price | SuggestedPostPrice | Optional | Optional. Proposed price of the post. If the field is omitted, then the post is unpaid. |
| send_date | Integer | Optional | Optional. Proposed send date of the post. If the field is omitted, then the post can be published at any time within 30 days at the sole discretion of the user or administrator who approves it. |
