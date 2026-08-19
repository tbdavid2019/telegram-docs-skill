# Type: RichTextMention

**Category**: Rich messages

**Description**: A mention by a username.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richtextmention)

**Subtype of**: RichText

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the rich text, always "mention" |
| text | RichText | Yes | The text |
| username | String | Yes | The username |
