# Method: answerGuestQuery

**Category**: Available methods

**Description**: Use this method to reply to a received guest message. On success, a SentGuestMessage object is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#answerguestquery)

**Returns**: SentGuestMessage

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| guest_query_id | String | Yes | Unique identifier for the query to be answered |
| result | InlineQueryResult | Yes | A JSON-serialized object describing the message to be sent |
