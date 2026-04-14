# Type: OwnedGiftUnique

**Category**: Available types

**Description**: Describes a unique gift received and owned by a user or a chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#ownedgiftunique)

**Subtype of**: OwnedGift

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the gift, always "unique" |
| gift | UniqueGift | Yes | Information about the unique gift |
| owned_gift_id | String | Optional | Optional. Unique identifier of the received gift for the bot; for gifts received on behalf of business accounts only |
| sender_user | User | Optional | Optional. Sender of the gift if it is a known user |
| send_date | Integer | Yes | Date the gift was sent in Unix time |
| is_saved | Boolean | Optional | Optional. True, if the gift is displayed on the account's profile page; for gifts received on behalf of business accounts only |
| can_be_transferred | Boolean | Optional | Optional. True, if the gift can be transferred to another owner; for gifts received on behalf of business accounts only |
| transfer_star_count | Integer | Optional | Optional. Number of Telegram Stars that must be paid to transfer the gift; omitted if the bot cannot transfer the gift |
| next_transfer_date | Integer | Optional | Optional. Point in time (Unix timestamp) when the gift can be transferred. If it is in the past, then the gift can be transferred now |
