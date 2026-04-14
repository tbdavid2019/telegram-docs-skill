# Method: setStickerMaskPosition

**Category**: Stickers

**Description**: Use this method to change the mask position of a mask sticker. The sticker must belong to a sticker set that was created by the bot. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setstickermaskposition)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| sticker | String | Yes | File identifier of the sticker |
| mask_position | MaskPosition | Optional | A JSON-serialized object with the position where the mask should be placed on faces. Omit the parameter to remove the mask position. |
