# Type: ChatMemberRestricted

**Category**: Available types

**Description**: Represents a chat member that is under certain restrictions in the chat. Supergroups only.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#chatmemberrestricted)

**Subtype of**: ChatMember

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| status | String | Yes | The member's status in the chat, always "restricted" |
| tag | String | Optional | Optional. Tag of the member |
| user | User | Yes | Information about the user |
| is_member | Boolean | Yes | True, if the user is a member of the chat at the moment of the request |
| can_send_messages | Boolean | Yes | True, if the user is allowed to send text messages, contacts, giveaways, giveaway winners, invoices, locations and venues |
| can_send_audios | Boolean | Yes | True, if the user is allowed to send audios |
| can_send_documents | Boolean | Yes | True, if the user is allowed to send documents |
| can_send_photos | Boolean | Yes | True, if the user is allowed to send photos |
| can_send_videos | Boolean | Yes | True, if the user is allowed to send videos |
| can_send_video_notes | Boolean | Yes | True, if the user is allowed to send video notes |
| can_send_voice_notes | Boolean | Yes | True, if the user is allowed to send voice notes |
| can_send_polls | Boolean | Yes | True, if the user is allowed to send polls and checklists |
| can_send_other_messages | Boolean | Yes | True, if the user is allowed to send animations, games, stickers and use inline bots |
| can_add_web_page_previews | Boolean | Yes | True, if the user is allowed to add web page previews to their messages |
| can_edit_tag | Boolean | Yes | True, if the user is allowed to edit their own tag |
| can_change_info | Boolean | Yes | True, if the user is allowed to change the chat title, photo and other settings |
| can_invite_users | Boolean | Yes | True, if the user is allowed to invite new users to the chat |
| can_pin_messages | Boolean | Yes | True, if the user is allowed to pin messages |
| can_manage_topics | Boolean | Yes | True, if the user is allowed to create forum topics |
| until_date | Integer | Yes | Date when restrictions will be lifted for this user; Unix time. If 0, then the user is restricted forever |
