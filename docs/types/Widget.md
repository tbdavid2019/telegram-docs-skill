# Type: Widget

**Category**: Available types

**Description**: This object describes an HTML widget.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#widget)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Optional | Optional. Unique identifier of the shared widget, which can be used to send the widget again using the method sendSharedWidget; omitted if the widget isn't shared |
| width | Integer | Optional | Optional. Width of the widget in logical pixels; omitted if the widget must occupy the whole width of the message bubble |
| height | Integer | Optional | Optional. Height of the widget in logical pixels; omitted if the height of the widget isn't fixed |
| html | String | Yes | HTML code of the widget |
| public_data | String | Optional | Optional. Public data of the widget, which is available wherever the widget is shown. All messages with a shared widget have the same public data. |
| chat_data | String | Optional | Optional. Data of the widget, which is specific to the message |
