# Method: editMessageChecklist

**Category**: Updating messages

**Description**: Use this method to edit a checklist on behalf of a connected business account. On success, the edited Message is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#editmessagechecklist)

**Returns**: Message

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection on behalf of which the message will be sent |
| chat_id | Integer | Yes | Unique identifier for the target chat |
| message_id | Integer | Yes | Unique identifier for the target message |
| checklist | InputChecklist | Yes | A JSON-serialized object for the new checklist |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for the new inline keyboard for the message |
