# Method: sendChecklist

**Category**: Available methods

**Description**: Use this method to send a checklist on behalf of a connected business account. On success, the sent Message is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sendchecklist)

**Returns**: Message

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection on behalf of which the message will be sent |
| chat_id | Integer | Yes | Unique identifier for the target chat |
| checklist | InputChecklist | Yes | A JSON-serialized object for the checklist to send |
| disable_notification | Boolean | Optional | Sends the message silently. Users will receive a notification with no sound. |
| protect_content | Boolean | Optional | Protects the contents of the sent message from forwarding and saving |
| message_effect_id | String | Optional | Unique identifier of the message effect to be added to the message |
| reply_parameters | ReplyParameters | Optional | A JSON-serialized object for description of the message to reply to |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for an inline keyboard |
