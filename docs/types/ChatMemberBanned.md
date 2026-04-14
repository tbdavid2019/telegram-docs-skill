# Type: ChatMemberBanned

**Category**: Available types

**Description**: Represents a chat member that was banned in the chat and can't return to the chat or view chat messages.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatmemberbanned)

**Subtype of**: ChatMember

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| status | String | Yes | The member's status in the chat, always "kicked" |
| user | User | Yes | Information about the user |
| until_date | Integer | Yes | Date when restrictions will be lifted for this user; Unix time. If 0, then the user is banned forever |
