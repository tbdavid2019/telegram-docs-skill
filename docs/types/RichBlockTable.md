# Type: RichBlockTable

**Category**: Rich messages

**Description**: A table, corresponding to the HTML tag <table>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblocktable)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "table" |
| cells | Array of Array of RichBlockTableCell | Yes | Cells of the table |
| is_bordered | Boolean | Optional | Optional. True, if the table has borders |
| is_striped | Boolean | Optional | Optional. True, if the table is striped |
| caption | RichText | Optional | Optional. Caption of the table |
