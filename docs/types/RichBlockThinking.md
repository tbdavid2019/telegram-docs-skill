# Type: RichBlockThinking

**Category**: Rich messages

**Description**: A block with a "Thinking..." placeholder, corresponding to the custom HTML tag <tg-thinking>. The block may be used only in sendRichMessageDraft, therefore it can't be received in messages. See https://t.me/addemoji/AIActions for examples of custom emoji, which are recommended for usage in the block.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockthinking)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "thinking" |
| text | RichText | Yes | Text of the block. See https://t.me/addemoji/AIActions for examples of custom emoji, which are recommended for usage in the block. |
