# Type: StickerSet

**Category**: Stickers

**Description**: This object represents a sticker set.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#stickerset)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| name | String | Yes | Sticker set name |
| title | String | Yes | Sticker set title |
| sticker_type | String | Yes | Type of stickers in the set, currently one of "regular", "mask", "custom_emoji" |
| stickers | Array of Sticker | Yes | List of all set stickers |
| thumbnail | PhotoSize | Optional | Optional. Sticker set thumbnail in the .WEBP, .TGS, or .WEBM format |
