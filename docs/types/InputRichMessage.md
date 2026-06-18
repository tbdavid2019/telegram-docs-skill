# Type: InputRichMessage

**Category**: Rich messages

**Description**: Describes a rich message to be sent. Exactly one of the fields html or markdown must be used.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichmessage)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| html | String | Optional | Optional. Content of the rich message to send described using HTML formatting. See rich message formatting options for more details. |
| markdown | String | Optional | Optional. Content of the rich message to send described using Markdown formatting. See rich message formatting options for more details. |
| is_rtl | Boolean | Optional | Optional. Pass True if the rich message must be shown right-to-left |
| skip_entity_detection | Boolean | Optional | Optional. Pass True to skip automatic detection of entities (e.g., URLs, email addresses, username mentions, hashtags, cashtags, bot commands, or phone numbers) in the text |
