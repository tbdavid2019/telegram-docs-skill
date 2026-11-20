# Type: WidgetQuery

**Category**: Available types

**Description**: This object represents an incoming query from a widget in a message sent by the bot or via the bot. Use answerWidgetQuery to answer the query. Each user can send at most 5 queries per 5 seconds to the bot from all its widgets.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#widgetquery)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique identifier for this query |
| from | User | Yes | Sender |
| chat | Chat | Optional | Optional. Chat with the message containing the widget; omitted if the widget is in an inline message |
| message_id | Integer | Optional | Optional. Identifier of the message containing the widget; omitted if the widget is in an inline message |
| inline_message_id | String | Optional | Optional. Identifier of the inline message containing the widget |
| chat_instance | String | Yes | Global identifier, uniquely corresponding to the chat to which the message with the widget was sent |
| chat_type | String | Optional | Optional. For widgets in inline messages, type of the chat to which the message was sent. Can be either "sender" for a private chat with the inline query sender, "private", "group", "supergroup", or "channel". |
| type | WidgetQueryType | Yes | Type of the query |
| data | String | Yes | Data of the query, 1-64 bytes |
| widget_id | String | Optional | Optional. Unique identifier of the shared widget, which sent the query; omitted if the widget isn't shared |
