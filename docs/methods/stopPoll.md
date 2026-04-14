# Method: stopPoll

**Category**: Updating messages

**Description**: Use this method to stop a poll which was sent by the bot. On success, the stopped Poll is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#stoppoll)

**Returns**: Poll

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Optional | Unique identifier of the business connection on behalf of which the message to be edited was sent |
| chat_id | Integer or String | Yes | Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| message_id | Integer | Yes | Identifier of the original message with the poll |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for a new message inline keyboard. |
