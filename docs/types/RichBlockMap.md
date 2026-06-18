# Type: RichBlockMap

**Category**: Rich messages

**Description**: A block with a map, corresponding to the custom HTML tag <tg-map>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockmap)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "map" |
| location | Location | Yes | Location of the center of the map |
| zoom | Integer | Yes | Map zoom level; 13-20 |
| width | Integer | Yes | Expected width of the map |
| height | Integer | Yes | Expected height of the map |
| caption | RichBlockCaption | Optional | Optional. Caption of the block |
