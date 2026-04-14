# Type: BotCommandScopeChat

**Category**: Available types

**Description**: Represents the scope of bot commands, covering a specific chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#botcommandscopechat)

**Subtype of**: BotCommandScope

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Scope type, must be chat |
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup (in the format @supergroupusername). Channel direct messages chats and channel chats aren't supported. |
