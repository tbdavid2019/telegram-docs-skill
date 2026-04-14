# Type: StoryAreaTypeSuggestedReaction

**Category**: Available types

**Description**: Describes a story area pointing to a suggested reaction. Currently, a story can have up to 5 suggested reaction areas.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#storyareatypesuggestedreaction)

**Subtype of**: StoryAreaType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the area, always "suggested_reaction" |
| reaction_type | ReactionType | Yes | Type of the reaction |
| is_dark | Boolean | Optional | Optional. Pass True if the reaction area has a dark background |
| is_flipped | Boolean | Optional | Optional. Pass True if reaction area corner is flipped |
