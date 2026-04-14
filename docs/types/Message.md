# Type: Message

**Category**: Available types

**Description**: This object represents a message.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#message)

**Subtype of**: MaybeInaccessibleMessage

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| message_id | Integer | Yes | Unique message identifier inside this chat. In specific instances (e.g., message containing a video sent to a big chat), the server might automatically schedule a message instead of sending it immediately. In such cases, this field will be 0 and the relevant message will be unusable until it is actually sent |
| message_thread_id | Integer | Optional | Optional. Unique identifier of a message thread or forum topic to which the message belongs; for supergroups and private chats only |
| direct_messages_topic | DirectMessagesTopic | Optional | Optional. Information about the direct messages chat topic that contains the message |
| from | User | Optional | Optional. Sender of the message; may be empty for messages sent to channels. For backward compatibility, if the message was sent on behalf of a chat, the field contains a fake sender user in non-channel chats |
| sender_chat | Chat | Optional | Optional. Sender of the message when sent on behalf of a chat. For example, the supergroup itself for messages sent by its anonymous administrators or a linked channel for messages automatically forwarded to the channel's discussion group. For backward compatibility, if the message was sent on behalf of a chat, the field from contains a fake sender user in non-channel chats. |
| sender_boost_count | Integer | Optional | Optional. If the sender of the message boosted the chat, the number of boosts added by the user |
| sender_business_bot | User | Optional | Optional. The bot that actually sent the message on behalf of the business account. Available only for outgoing messages sent on behalf of the connected business account. |
| sender_tag | String | Optional | Optional. Tag or custom title of the sender of the message; for supergroups only |
| date | Integer | Yes | Date the message was sent in Unix time. It is always a positive number, representing a valid date. |
| business_connection_id | String | Optional | Optional. Unique identifier of the business connection from which the message was received. If non-empty, the message belongs to a chat of the corresponding business account that is independent from any potential bot chat which might share the same identifier. |
| chat | Chat | Yes | Chat the message belongs to |
| forward_origin | MessageOrigin | Optional | Optional. Information about the original message for forwarded messages |
| is_topic_message | Boolean | Optional | Optional. True, if the message is sent to a topic in a forum supergroup or a private chat with the bot |
| is_automatic_forward | Boolean | Optional | Optional. True, if the message is a channel post that was automatically forwarded to the connected discussion group |
| reply_to_message | Message | Optional | Optional. For replies in the same chat and message thread, the original message. Note that the Message object in this field will not contain further reply_to_message fields even if it itself is a reply. |
| external_reply | ExternalReplyInfo | Optional | Optional. Information about the message that is being replied to, which may come from another chat or forum topic |
| quote | TextQuote | Optional | Optional. For replies that quote part of the original message, the quoted part of the message |
| reply_to_story | Story | Optional | Optional. For replies to a story, the original story |
| reply_to_checklist_task_id | Integer | Optional | Optional. Identifier of the specific checklist task that is being replied to |
| reply_to_poll_option_id | String | Optional | Optional. Persistent identifier of the specific poll option that is being replied to |
| via_bot | User | Optional | Optional. Bot through which the message was sent |
| edit_date | Integer | Optional | Optional. Date the message was last edited in Unix time |
| has_protected_content | Boolean | Optional | Optional. True, if the message can't be forwarded |
| is_from_offline | Boolean | Optional | Optional. True, if the message was sent by an implicit action, for example, as an away or a greeting business message, or as a scheduled message |
| is_paid_post | Boolean | Optional | Optional. True, if the message is a paid post. Note that such posts must not be deleted for 24 hours to receive the payment and can't be edited. |
| media_group_id | String | Optional | Optional. The unique identifier inside this chat of a media message group this message belongs to |
| author_signature | String | Optional | Optional. Signature of the post author for messages in channels, or the custom title of an anonymous group administrator |
| paid_star_count | Integer | Optional | Optional. The number of Telegram Stars that were paid by the sender of the message to send it |
| text | String | Optional | Optional. For text messages, the actual UTF-8 text of the message |
| entities | Array of MessageEntity | Optional | Optional. For text messages, special entities like usernames, URLs, bot commands, etc. that appear in the text |
| link_preview_options | LinkPreviewOptions | Optional | Optional. Options used for link preview generation for the message, if it is a text message and link preview options were changed |
| suggested_post_info | SuggestedPostInfo | Optional | Optional. Information about suggested post parameters if the message is a suggested post in a channel direct messages chat. If the message is an approved or declined suggested post, then it can't be edited. |
| effect_id | String | Optional | Optional. Unique identifier of the message effect added to the message |
| animation | Animation | Optional | Optional. Message is an animation, information about the animation. For backward compatibility, when this field is set, the document field will also be set |
| audio | Audio | Optional | Optional. Message is an audio file, information about the file |
| document | Document | Optional | Optional. Message is a general file, information about the file |
| paid_media | PaidMediaInfo | Optional | Optional. Message contains paid media; information about the paid media |
| photo | Array of PhotoSize | Optional | Optional. Message is a photo, available sizes of the photo |
| sticker | Sticker | Optional | Optional. Message is a sticker, information about the sticker |
| story | Story | Optional | Optional. Message is a forwarded story |
| video | Video | Optional | Optional. Message is a video, information about the video |
| video_note | VideoNote | Optional | Optional. Message is a video note, information about the video message |
| voice | Voice | Optional | Optional. Message is a voice message, information about the file |
| caption | String | Optional | Optional. Caption for the animation, audio, document, paid media, photo, video or voice |
| caption_entities | Array of MessageEntity | Optional | Optional. For messages with a caption, special entities like usernames, URLs, bot commands, etc. that appear in the caption |
| show_caption_above_media | Boolean | Optional | Optional. True, if the caption must be shown above the message media |
| has_media_spoiler | Boolean | Optional | Optional. True, if the message media is covered by a spoiler animation |
| checklist | Checklist | Optional | Optional. Message is a checklist |
| contact | Contact | Optional | Optional. Message is a shared contact, information about the contact |
| dice | Dice | Optional | Optional. Message is a dice with random value |
| game | Game | Optional | Optional. Message is a game, information about the game. More about games: https://core.telegram.org/bots/api#games |
| poll | Poll | Optional | Optional. Message is a native poll, information about the poll |
| venue | Venue | Optional | Optional. Message is a venue, information about the venue. For backward compatibility, when this field is set, the location field will also be set |
| location | Location | Optional | Optional. Message is a shared location, information about the location |
| new_chat_members | Array of User | Optional | Optional. New members that were added to the group or supergroup and information about them (the bot itself may be one of these members) |
| left_chat_member | User | Optional | Optional. A member was removed from the group, information about them (this member may be the bot itself) |
| chat_owner_left | ChatOwnerLeft | Optional | Optional. Service message: chat owner has left |
| chat_owner_changed | ChatOwnerChanged | Optional | Optional. Service message: chat owner has changed |
| new_chat_title | String | Optional | Optional. A chat title was changed to this value |
| new_chat_photo | Array of PhotoSize | Optional | Optional. A chat photo was change to this value |
| delete_chat_photo | Boolean | Optional | Optional. Service message: the chat photo was deleted |
| group_chat_created | Boolean | Optional | Optional. Service message: the group has been created |
| supergroup_chat_created | Boolean | Optional | Optional. Service message: the supergroup has been created. This field can't be received in a message coming through updates, because bot can't be a member of a supergroup when it is created. It can only be found in reply_to_message if someone replies to a very first message in a directly created supergroup. |
| channel_chat_created | Boolean | Optional | Optional. Service message: the channel has been created. This field can't be received in a message coming through updates, because bot can't be a member of a channel when it is created. It can only be found in reply_to_message if someone replies to a very first message in a channel. |
| message_auto_delete_timer_changed | MessageAutoDeleteTimerChanged | Optional | Optional. Service message: auto-delete timer settings changed in the chat |
| migrate_to_chat_id | Integer | Optional | Optional. The group has been migrated to a supergroup with the specified identifier. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. |
| migrate_from_chat_id | Integer | Optional | Optional. The supergroup has been migrated from a group with the specified identifier. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. |
| pinned_message | MaybeInaccessibleMessage | Optional | Optional. Specified message was pinned. Note that the Message object in this field will not contain further reply_to_message fields even if it itself is a reply. |
| invoice | Invoice | Optional | Optional. Message is an invoice for a payment, information about the invoice. More about payments: https://core.telegram.org/bots/api#payments |
| successful_payment | SuccessfulPayment | Optional | Optional. Message is a service message about a successful payment, information about the payment. More about payments: https://core.telegram.org/bots/api#payments |
| refunded_payment | RefundedPayment | Optional | Optional. Message is a service message about a refunded payment, information about the payment. More about payments: https://core.telegram.org/bots/api#payments |
| users_shared | UsersShared | Optional | Optional. Service message: users were shared with the bot |
| chat_shared | ChatShared | Optional | Optional. Service message: a chat was shared with the bot |
| gift | GiftInfo | Optional | Optional. Service message: a regular gift was sent or received |
| unique_gift | UniqueGiftInfo | Optional | Optional. Service message: a unique gift was sent or received |
| gift_upgrade_sent | GiftInfo | Optional | Optional. Service message: upgrade of a gift was purchased after the gift was sent |
| connected_website | String | Optional | Optional. The domain name of the website on which the user has logged in. More about Telegram Login: https://core.telegram.org/widgets/login |
| write_access_allowed | WriteAccessAllowed | Optional | Optional. Service message: the user allowed the bot to write messages after adding it to the attachment or side menu, launching a Web App from a link, or accepting an explicit request from a Web App sent by the method requestWriteAccess |
| passport_data | PassportData | Optional | Optional. Telegram Passport data |
| proximity_alert_triggered | ProximityAlertTriggered | Optional | Optional. Service message. A user in the chat triggered another user's proximity alert while sharing Live Location. |
| boost_added | ChatBoostAdded | Optional | Optional. Service message: user boosted the chat |
| chat_background_set | ChatBackground | Optional | Optional. Service message: chat background set |
| checklist_tasks_done | ChecklistTasksDone | Optional | Optional. Service message: some tasks in a checklist were marked as done or not done |
| checklist_tasks_added | ChecklistTasksAdded | Optional | Optional. Service message: tasks were added to a checklist |
| direct_message_price_changed | DirectMessagePriceChanged | Optional | Optional. Service message: the price for paid messages in the corresponding direct messages chat of a channel has changed |
| forum_topic_created | ForumTopicCreated | Optional | Optional. Service message: forum topic created |
| forum_topic_edited | ForumTopicEdited | Optional | Optional. Service message: forum topic edited |
| forum_topic_closed | ForumTopicClosed | Optional | Optional. Service message: forum topic closed |
| forum_topic_reopened | ForumTopicReopened | Optional | Optional. Service message: forum topic reopened |
| general_forum_topic_hidden | GeneralForumTopicHidden | Optional | Optional. Service message: the 'General' forum topic hidden |
| general_forum_topic_unhidden | GeneralForumTopicUnhidden | Optional | Optional. Service message: the 'General' forum topic unhidden |
| giveaway_created | GiveawayCreated | Optional | Optional. Service message: a scheduled giveaway was created |
| giveaway | Giveaway | Optional | Optional. The message is a scheduled giveaway message |
| giveaway_winners | GiveawayWinners | Optional | Optional. A giveaway with public winners was completed |
| giveaway_completed | GiveawayCompleted | Optional | Optional. Service message: a giveaway without public winners was completed |
| managed_bot_created | ManagedBotCreated | Optional | Optional. Service message: user created a bot that will be managed by the current bot |
| paid_message_price_changed | PaidMessagePriceChanged | Optional | Optional. Service message: the price for paid messages has changed in the chat |
| poll_option_added | PollOptionAdded | Optional | Optional. Service message: answer option was added to a poll |
| poll_option_deleted | PollOptionDeleted | Optional | Optional. Service message: answer option was deleted from a poll |
| suggested_post_approved | SuggestedPostApproved | Optional | Optional. Service message: a suggested post was approved |
| suggested_post_approval_failed | SuggestedPostApprovalFailed | Optional | Optional. Service message: approval of a suggested post has failed |
| suggested_post_declined | SuggestedPostDeclined | Optional | Optional. Service message: a suggested post was declined |
| suggested_post_paid | SuggestedPostPaid | Optional | Optional. Service message: payment for a suggested post was received |
| suggested_post_refunded | SuggestedPostRefunded | Optional | Optional. Service message: payment for a suggested post was refunded |
| video_chat_scheduled | VideoChatScheduled | Optional | Optional. Service message: video chat scheduled |
| video_chat_started | VideoChatStarted | Optional | Optional. Service message: video chat started |
| video_chat_ended | VideoChatEnded | Optional | Optional. Service message: video chat ended |
| video_chat_participants_invited | VideoChatParticipantsInvited | Optional | Optional. Service message: new participants invited to a video chat |
| web_app_data | WebAppData | Optional | Optional. Service message: data sent by a Web App |
| reply_markup | InlineKeyboardMarkup | Optional | Optional. Inline keyboard attached to the message. login_url buttons are represented as ordinary url buttons. |
