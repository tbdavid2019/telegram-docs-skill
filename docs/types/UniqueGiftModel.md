# Type: UniqueGiftModel

**Category**: Available types

**Description**: This object describes the model of a unique gift.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#uniquegiftmodel)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| name | String | Yes | Name of the model |
| sticker | Sticker | Yes | The sticker that represents the unique gift |
| rarity_per_mille | Integer | Yes | The number of unique gifts that receive this model for every 1000 gift upgrades. Always 0 for crafted gifts. |
| rarity | String | Optional | Optional. Rarity of the model if it is a crafted model. Currently, can be "uncommon", "rare", "epic", or "legendary". |
