# Type: ForumTopic

**Category**: Available types

**Description**: This object represents a forum topic.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#forumtopic)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| message_thread_id | Integer | Yes | Unique identifier of the forum topic |
| name | String | Yes | Name of the topic |
| icon_color | Integer | Yes | Color of the topic icon in RGB format |
| icon_custom_emoji_id | String | Optional | Optional. Unique identifier of the custom emoji shown as the topic icon |
| is_name_implicit | Boolean | Optional | Optional. True, if the name of the topic wasn't specified explicitly by its creator and likely needs to be changed by the bot |
