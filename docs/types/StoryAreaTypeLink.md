# Type: StoryAreaTypeLink

**Category**: Available types

**Description**: Describes a story area pointing to an HTTP or tg:// link. Currently, a story can have up to 3 link areas.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#storyareatypelink)

**Subtype of**: StoryAreaType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the area, always "link" |
| url | String | Yes | HTTP or tg:// URL to be opened when the area is clicked |
