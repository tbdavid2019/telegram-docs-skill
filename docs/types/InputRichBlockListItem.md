# Type: InputRichBlockListItem

**Category**: Rich messages

**Description**: An item of a list to be sent.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblocklistitem)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| blocks | Array of InputRichBlock | Yes | The content of the item |
| has_checkbox | Boolean | Optional | Optional. Pass True if the item has a checkbox |
| is_checked | Boolean | Optional | Optional. Pass True if the item has a checked checkbox |
| value | Integer | Optional | Optional. For ordered lists, the numeric value of the item label |
| type | String | Optional | Optional. For ordered lists, the type of the item label; must be one of "a" for lowercase letters, "A" for uppercase letters, "i" for lowercase Roman numerals, "I" for uppercase Roman numerals, or "1" for decimal numbers |
