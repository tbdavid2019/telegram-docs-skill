# Type: ExternalReplyInfo

**Category**: Available types

**Description**: This object contains information about a message that is being replied to, which may come from another chat or forum topic.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#externalreplyinfo)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| origin | MessageOrigin | Yes | Origin of the message replied to by the given message |
| chat | Chat | Optional | Optional. Chat the original message belongs to. Available only if the chat is a supergroup or a channel. |
| message_id | Integer | Optional | Optional. Unique message identifier inside the original chat. Available only if the original chat is a supergroup or a channel. |
| link_preview_options | LinkPreviewOptions | Optional | Optional. Options used for link preview generation for the original message, if it is a text message |
| animation | Animation | Optional | Optional. Message is an animation, information about the animation |
| audio | Audio | Optional | Optional. Message is an audio file, information about the file |
| document | Document | Optional | Optional. Message is a general file, information about the file |
| paid_media | PaidMediaInfo | Optional | Optional. Message contains paid media; information about the paid media |
| photo | Array of PhotoSize | Optional | Optional. Message is a photo, available sizes of the photo |
| sticker | Sticker | Optional | Optional. Message is a sticker, information about the sticker |
| story | Story | Optional | Optional. Message is a forwarded story |
| video | Video | Optional | Optional. Message is a video, information about the video |
| video_note | VideoNote | Optional | Optional. Message is a video note, information about the video message |
| voice | Voice | Optional | Optional. Message is a voice message, information about the file |
| has_media_spoiler | Boolean | Optional | Optional. True, if the message media is covered by a spoiler animation |
| checklist | Checklist | Optional | Optional. Message is a checklist |
| contact | Contact | Optional | Optional. Message is a shared contact, information about the contact |
| dice | Dice | Optional | Optional. Message is a dice with random value |
| game | Game | Optional | Optional. Message is a game, information about the game. More about games: https://core.telegram.org/bots/api#games |
| giveaway | Giveaway | Optional | Optional. Message is a scheduled giveaway, information about the giveaway |
| giveaway_winners | GiveawayWinners | Optional | Optional. A giveaway with public winners was completed |
| invoice | Invoice | Optional | Optional. Message is an invoice for a payment, information about the invoice. More about payments: https://core.telegram.org/bots/api#payments |
| location | Location | Optional | Optional. Message is a shared location, information about the location |
| poll | Poll | Optional | Optional. Message is a native poll, information about the poll |
| venue | Venue | Optional | Optional. Message is a venue, information about the venue |
