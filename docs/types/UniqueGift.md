# Type: UniqueGift

**Category**: Available types

**Description**: This object describes a unique gift that was upgraded from a regular gift.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#uniquegift)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| gift_id | String | Yes | Identifier of the regular gift from which the gift was upgraded |
| base_name | String | Yes | Human-readable name of the regular gift from which this unique gift was upgraded |
| name | String | Yes | Unique name of the gift. This name can be used in https://t.me/nft/... links and story areas |
| number | Integer | Yes | Unique number of the upgraded gift among gifts upgraded from the same regular gift |
| model | UniqueGiftModel | Yes | Model of the gift |
| symbol | UniqueGiftSymbol | Yes | Symbol of the gift |
| backdrop | UniqueGiftBackdrop | Yes | Backdrop of the gift |
| is_premium | Boolean | Optional | Optional. True, if the original regular gift was exclusively purchaseable by Telegram Premium subscribers |
| is_burned | Boolean | Optional | Optional. True, if the gift was used to craft another gift and isn't available anymore |
| is_from_blockchain | Boolean | Optional | Optional. True, if the gift is assigned from the TON blockchain and can't be resold or transferred in Telegram |
| colors | UniqueGiftColors | Optional | Optional. The color scheme that can be used by the gift's owner for the chat's name, replies to messages and link previews; for business account gifts and gifts that are currently on sale only |
| publisher_chat | Chat | Optional | Optional. Information about the chat that published the gift |
