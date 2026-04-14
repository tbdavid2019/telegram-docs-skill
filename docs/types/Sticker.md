# Type: Sticker

**Category**: Stickers

**Description**: This object represents a sticker.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#sticker)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| file_id | String | Yes | Identifier for this file, which can be used to download or reuse the file |
| file_unique_id | String | Yes | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can't be used to download or reuse the file. |
| type | String | Yes | Type of the sticker, currently one of "regular", "mask", "custom_emoji". The type of the sticker is independent from its format, which is determined by the fields is_animated and is_video. |
| width | Integer | Yes | Sticker width |
| height | Integer | Yes | Sticker height |
| is_animated | Boolean | Yes | True, if the sticker is animated |
| is_video | Boolean | Yes | True, if the sticker is a video sticker |
| thumbnail | PhotoSize | Optional | Optional. Sticker thumbnail in the .WEBP or .JPG format |
| emoji | String | Optional | Optional. Emoji associated with the sticker |
| set_name | String | Optional | Optional. Name of the sticker set to which the sticker belongs |
| premium_animation | File | Optional | Optional. For premium regular stickers, premium animation for the sticker |
| mask_position | MaskPosition | Optional | Optional. For mask stickers, the position where the mask should be placed |
| custom_emoji_id | String | Optional | Optional. For custom emoji stickers, unique identifier of the custom emoji |
| needs_repainting | Boolean | Optional | Optional. True, if the sticker must be repainted to a text color in messages, the color of the Telegram Premium badge in emoji status, white color on chat photos, or another appropriate color in other places |
| file_size | Integer | Optional | Optional. File size in bytes |
