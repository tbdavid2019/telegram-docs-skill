# Type: ForumTopicCreated

**Category**: Available types

**Description**: This object represents a service message about a new forum topic created in the chat.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#forumtopiccreated)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| name | String | Yes | Name of the topic |
| icon_color | Integer | Yes | Color of the topic icon in RGB format |
| icon_custom_emoji_id | String | Optional | Optional. Unique identifier of the custom emoji shown as the topic icon |
| is_name_implicit | Boolean | Optional | Optional. True, if the name of the topic wasn't specified explicitly by its creator and likely needs to be changed by the bot |
