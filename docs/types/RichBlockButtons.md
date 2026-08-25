# Type: RichBlockButtons

**Category**: Rich messages

**Description**: A block containing a list of buttons that are shown in one row, corresponding to the custom HTML tag <tg-button-row>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockbuttons)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "buttons" |
| buttons | Array of RichMessageButton | Yes | The buttons |
| align | String | Optional | Optional. Horizontal alignment of the buttons. Currently, must be one of "left", "center", or "right". |
