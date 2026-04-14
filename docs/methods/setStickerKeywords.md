# Method: setStickerKeywords

**Category**: Stickers

**Description**: Use this method to change search keywords assigned to a regular or custom emoji sticker. The sticker must belong to a sticker set created by the bot. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setstickerkeywords)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| sticker | String | Yes | File identifier of the sticker |
| keywords | Array of String | Optional | A JSON-serialized list of 0-20 search keywords for the sticker with total length of up to 64 characters |
