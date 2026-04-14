# Type: BotCommandScopeChatAdministrators

**Category**: Available types

**Description**: Represents the scope of bot commands, covering all administrators of a specific group or supergroup chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#botcommandscopechatadministrators)

**Subtype of**: BotCommandScope

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Scope type, must be chat_administrators |
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup (in the format @supergroupusername). Channel direct messages chats and channel chats aren't supported. |
