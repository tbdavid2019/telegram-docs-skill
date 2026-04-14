# Method: uploadStickerFile

**Category**: Stickers

**Description**: Use this method to upload a file with a sticker for later use in the createNewStickerSet, addStickerToSet, or replaceStickerInSet methods (the file can be used multiple times). Returns the uploaded File on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#uploadstickerfile)

**Returns**: File

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| user_id | Integer | Yes | User identifier of sticker file owner |
| sticker | InputFile | Yes | A file with the sticker in .WEBP, .PNG, .TGS, or .WEBM format. See https://core.telegram.org/stickers for technical requirements. More information on Sending Files: https://core.telegram.org/bots/api#sending-files |
| sticker_format | String | Yes | Format of the sticker, must be one of "static", "animated", "video" |
