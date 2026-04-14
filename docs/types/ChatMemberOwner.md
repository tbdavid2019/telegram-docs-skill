# Type: ChatMemberOwner

**Category**: Available types

**Description**: Represents a chat member that owns the chat and has all administrator privileges.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatmemberowner)

**Subtype of**: ChatMember

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| status | String | Yes | The member's status in the chat, always "creator" |
| user | User | Yes | Information about the user |
| is_anonymous | Boolean | Yes | True, if the user's presence in the chat is hidden |
| custom_title | String | Optional | Optional. Custom title for this user |
