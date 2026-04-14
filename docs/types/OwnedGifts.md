# Type: OwnedGifts

**Category**: Available types

**Description**: Contains the list of gifts received and owned by a user or a chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#ownedgifts)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| total_count | Integer | Yes | The total number of gifts owned by the user or the chat |
| gifts | Array of OwnedGift | Yes | The list of gifts |
| next_offset | String | Optional | Optional. Offset for the next request. If empty, then there are no more results |
