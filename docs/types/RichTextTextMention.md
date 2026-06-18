# Type: RichTextTextMention

**Category**: Rich messages

**Description**: A mention of a Telegram user by their identifier.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richtexttextmention)

**Subtype of**: RichText

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the rich text, always "text_mention" |
| text | RichText | Yes | The text |
| user | User | Yes | The mentioned user |
