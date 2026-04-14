# Method: answerWebAppQuery

**Category**: Available methods

**Description**: Use this method to set the result of an interaction with a Web App and send a corresponding message on behalf of the user to the chat from which the query originated. On success, a SentWebAppMessage object is returned.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#answerwebappquery)

**Returns**: SentWebAppMessage

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| web_app_query_id | String | Yes | Unique identifier for the query to be answered |
| result | InlineQueryResult | Yes | A JSON-serialized object describing the message to be sent |
