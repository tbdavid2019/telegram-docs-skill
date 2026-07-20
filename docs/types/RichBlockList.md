# Type: RichBlockList

**Category**: Rich messages

**Description**: A list of blocks, corresponding to the HTML tag <ul> or <ol> with multiple nested tags <li>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblocklist)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "list" |
| items | Array of RichBlockListItem | Yes | Items of the list |
