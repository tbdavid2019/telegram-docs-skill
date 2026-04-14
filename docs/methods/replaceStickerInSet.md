# Method: replaceStickerInSet

**Category**: Stickers

**Description**: Use this method to replace an existing sticker in a sticker set with a new one. The method is equivalent to calling deleteStickerFromSet, then addStickerToSet, then setStickerPositionInSet. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#replacestickerinset)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| user_id | Integer | Yes | User identifier of the sticker set owner |
| name | String | Yes | Sticker set name |
| old_sticker | String | Yes | File identifier of the replaced sticker |
| sticker | InputSticker | Yes | A JSON-serialized object with information about the added sticker. If exactly the same sticker had already been added to the set, then the set remains unchanged. |
