# Method: getChatAdministrators

**Category**: Available methods

**Description**: Use this method to get a list of administrators in a chat. Returns an Array of ChatMember objects.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#getchatadministrators)

**Returns**: Array of ChatMember

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target supergroup or channel in the format @username |
| return_bots | Boolean | Optional | Pass True to additionally receive all bots that are administrators of the chat. By default, bots other than the current bot are omitted. |
