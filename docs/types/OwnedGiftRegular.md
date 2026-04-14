# Type: OwnedGiftRegular

**Category**: Available types

**Description**: Describes a regular gift owned by a user or a chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#ownedgiftregular)

**Subtype of**: OwnedGift

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the gift, always "regular" |
| gift | Gift | Yes | Information about the regular gift |
| owned_gift_id | String | Optional | Optional. Unique identifier of the gift for the bot; for gifts received on behalf of business accounts only |
| sender_user | User | Optional | Optional. Sender of the gift if it is a known user |
| send_date | Integer | Yes | Date the gift was sent in Unix time |
| text | String | Optional | Optional. Text of the message that was added to the gift |
| entities | Array of MessageEntity | Optional | Optional. Special entities that appear in the text |
| is_private | Boolean | Optional | Optional. True, if the sender and gift text are shown only to the gift receiver; otherwise, everyone will be able to see them |
| is_saved | Boolean | Optional | Optional. True, if the gift is displayed on the account's profile page; for gifts received on behalf of business accounts only |
| can_be_upgraded | Boolean | Optional | Optional. True, if the gift can be upgraded to a unique gift; for gifts received on behalf of business accounts only |
| was_refunded | Boolean | Optional | Optional. True, if the gift was refunded and isn't available anymore |
| convert_star_count | Integer | Optional | Optional. Number of Telegram Stars that can be claimed by the receiver instead of the gift; omitted if the gift cannot be converted to Telegram Stars; for gifts received on behalf of business accounts only |
| prepaid_upgrade_star_count | Integer | Optional | Optional. Number of Telegram Stars that were paid for the ability to upgrade the gift |
| is_upgrade_separate | Boolean | Optional | Optional. True, if the gift's upgrade was purchased after the gift was sent; for gifts received on behalf of business accounts only |
| unique_gift_number | Integer | Optional | Optional. Unique number reserved for this gift when upgraded. See the number field in UniqueGift |
