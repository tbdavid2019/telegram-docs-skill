# Type: ChatMemberMember

**Category**: Available types

**Description**: Represents a chat member that has no additional privileges or restrictions.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatmembermember)

**Subtype of**: ChatMember

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| status | String | Yes | The member's status in the chat, always "member" |
| tag | String | Optional | Optional. Tag of the member |
| user | User | Yes | Information about the user |
| until_date | Integer | Optional | Optional. Date when the user's subscription will expire; Unix time |
