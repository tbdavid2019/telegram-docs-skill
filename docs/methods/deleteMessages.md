# Method: deleteMessages

**Category**: Updating messages

**Description**: Use this method to delete multiple messages simultaneously. If some of the specified messages can't be found, they are skipped. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#deletemessages)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| message_ids | Array of Integer | Yes | A JSON-serialized list of 1-100 identifiers of messages to delete. See deleteMessage for limitations on which messages can be deleted |
