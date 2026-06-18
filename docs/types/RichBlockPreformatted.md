# Type: RichBlockPreformatted

**Category**: Rich messages

**Description**: A preformatted text block, corresponding to the nested HTML tags <pre> and <code>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblockpreformatted)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "pre" |
| text | RichText | Yes | Text of the block |
| language | String | Optional | Optional. The programming language of the text |
