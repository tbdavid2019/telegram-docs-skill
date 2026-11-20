# Type: InputSharedWidgetMessageContent

**Category**: Inline mode

**Description**: Represents the content of a message with a shared widget to be sent as the result of an inline query. Currently, widgets can't be sent in response to inline queries in the production environment.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputsharedwidgetmessagecontent)

**Subtype of**: InputMessageContent

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| widget_id | String | Yes | Unique identifier of the shared widget created by the bot |
| chat_data | String | Optional | Optional. Data of the widget, which is specific to the message, 0-1024 bytes |
| caption | String | Optional | Optional. Widget caption, 0-1024 characters after entities parsing |
| parse_mode | String | Optional | Optional. Mode for parsing entities in the widget caption. See formatting options for more details. |
| caption_entities | Array of MessageEntity | Optional | Optional. List of special entities that appear in the caption, which can be specified instead of parse_mode |
| show_caption_above_media | Boolean | Optional | Optional. Pass True if the caption must be shown above the widget |
