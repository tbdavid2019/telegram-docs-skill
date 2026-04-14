# Type: MessageEntity

**Category**: Available types

**Description**: This object represents one special entity in a text message. For example, hashtags, usernames, URLs, etc.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#messageentity)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the entity. Currently, can be "mention" (@username), "hashtag" (#hashtag or #hashtag@chatusername), "cashtag" ($USD or $USD@chatusername), "bot_command" (/start@jobs_bot), "url" (https://telegram.org), "email" (do-not-reply@telegram.org), "phone_number" (+1-212-555-0123), "bold" (bold text), "italic" (italic text), "underline" (underlined text), "strikethrough" (strikethrough text), "spoiler" (spoiler message), "blockquote" (block quotation), "expandable_blockquote" (collapsed-by-default block quotation), "code" (monowidth string), "pre" (monowidth block), "text_link" (for clickable text URLs), "text_mention" (for users without usernames), "custom_emoji" (for inline custom emoji stickers), or "date_time" (for formatted date and time) |
| offset | Integer | Yes | Offset in UTF-16 code units to the start of the entity |
| length | Integer | Yes | Length of the entity in UTF-16 code units |
| url | String | Optional | Optional. For "text_link" only, URL that will be opened after user taps on the text |
| user | User | Optional | Optional. For "text_mention" only, the mentioned user |
| language | String | Optional | Optional. For "pre" only, the programming language of the entity text |
| custom_emoji_id | String | Optional | Optional. For "custom_emoji" only, unique identifier of the custom emoji. Use getCustomEmojiStickers to get full information about the sticker |
| unix_time | Integer | Optional | Optional. For "date_time" only, the Unix time associated with the entity |
| date_time_format | String | Optional | Optional. For "date_time" only, the string that defines the formatting of the date and time. See date-time entity formatting for more details. |
