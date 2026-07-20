# Type: InputRichBlockMap

**Category**: Rich messages

**Description**: A block with a map, corresponding to the custom HTML tag <tg-map>. The map's width and height must not exceed 10000 in total. The width and height ratio must be at most 20.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockmap)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "map" |
| location | Location | Yes | Location of the center of the map |
| zoom | Integer | Yes | Map zoom level; 0-24 |
| width | Integer | Yes | Map width; 0-10000 |
| height | Integer | Yes | Map height; 0-10000 |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
