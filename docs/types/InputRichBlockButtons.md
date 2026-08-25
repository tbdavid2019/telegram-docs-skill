# Type: InputRichBlockButtons

**Category**: Rich messages

**Description**: A block containing a list of buttons that are shown in one row, corresponding to the custom HTML tag <tg-button-row>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputrichblockbuttons)

**Subtype of**: InputRichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "buttons" |
| buttons | Array of RichMessageButton | Yes | List of 1-8 buttons to send |
| align | String | Optional | Optional. Horizontal alignment of the buttons. Currently, must be one of "left", "center", or "right". |
