# Type: RichBlockTableCell

**Category**: Rich messages

**Description**: Cell in a table.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblocktablecell)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| text | RichText | Optional | Optional. Text in the cell. If omitted, then the cell is invisible. |
| is_header | Boolean | Optional | Optional. True, if the cell is a header cell |
| colspan | Integer | Optional | Optional. The number of columns the cell spans if it is bigger than 1 |
| rowspan | Integer | Optional | Optional. The number of rows the cell spans if it is bigger than 1 |
| align | String | Yes | Horizontal cell content alignment. Currently, must be one of "left", "center", or "right". |
| valign | String | Yes | Vertical cell content alignment. Currently, must be one of "top", "middle", or "bottom". |
