# Method: sendChatJoinRequestWebApp

**Category**: Available methods

**Description**: Use this method to process a received chat join request query by showing a Mini App to the user before deciding the outcome. Call answerChatJoinRequestQuery to resolve the join request query based on the user interaction with the Mini App. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sendchatjoinrequestwebapp)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| chat_join_request_query_id | String | Yes | Unique identifier of the join request query |
| web_app_url | String | Yes | The URL of the Mini App to be opened |
