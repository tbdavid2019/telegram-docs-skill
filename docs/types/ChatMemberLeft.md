# Type: ChatMemberLeft

**Category**: Available types

**Description**: Represents a chat member that isn't currently a member of the chat, but may join it themselves.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatmemberleft)

**Subtype of**: ChatMember

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| status | String | Yes | The member's status in the chat, always "left" |
| user | User | Yes | Information about the user |
