# Method: stopMessageLiveLocation

**Category**: Updating messages

**Description**: Use this method to stop updating a live location message before live_period expires. On success, if the message is not an inline message, the edited Message is returned, otherwise True is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#stopmessagelivelocation)

**Returns**: Message, Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Optional | Unique identifier of the business connection on behalf of which the message to be edited was sent |
| chat_id | Integer or String | Optional | Required if inline_message_id is not specified. Unique identifier for the target chat or username of the target channel (in the format @channelusername) |
| message_id | Integer | Optional | Required if inline_message_id is not specified. Identifier of the message with live location to stop |
| inline_message_id | String | Optional | Required if chat_id and message_id are not specified. Identifier of the inline message |
| reply_markup | InlineKeyboardMarkup | Optional | A JSON-serialized object for a new inline keyboard. |
