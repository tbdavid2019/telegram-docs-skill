# Type: SharedWidgetQuery

**Category**: Available types

**Description**: This object represents an incoming query from a forwarded message with a shared widget created by the bot. Use answerWidgetQuery to answer the query. Each user can send at most 5 queries per 5 seconds to the bot from all its widgets.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sharedwidgetquery)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique identifier for this query |
| from | User | Yes | Sender |
| type | WidgetQueryType | Yes | Type of the query |
| data | String | Yes | Data of the query, 1-64 bytes |
| widget_id | String | Yes | Unique identifier of the shared widget, which sent the query |
