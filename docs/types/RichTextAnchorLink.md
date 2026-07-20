# Type: RichTextAnchorLink

**Category**: Rich messages

**Description**: A link to an anchor.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richtextanchorlink)

**Subtype of**: RichText

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the rich text, always "anchor_link" |
| text | RichText | Yes | The link text |
| anchor_name | String | Yes | The name of the anchor. If the name is empty, then the link brings back to the top of the message. |
