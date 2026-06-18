# Type: RichTextCustomEmoji

**Category**: Rich messages

**Description**: A custom emoji.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richtextcustomemoji)

**Subtype of**: RichText

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the rich text, always "custom_emoji" |
| custom_emoji_id | String | Yes | Unique identifier of the custom emoji. Use getCustomEmojiStickers to get full information about the sticker. |
| alternative_text | String | Yes | Alternative emoji for the custom emoji |
