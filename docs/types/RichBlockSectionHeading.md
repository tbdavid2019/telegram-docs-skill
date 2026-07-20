# Type: RichBlockSectionHeading

**Category**: Rich messages

**Description**: A section heading, corresponding to the HTML tags <h1>, <h2>, <h3>, <h4>, <h5>, or <h6>.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richblocksectionheading)

**Subtype of**: RichBlock

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the block, always "heading" |
| text | RichText | Yes | Text of the block |
| size | Integer | Yes | Relative size of the text font; 1-6, 1 is the largest, 6 is the smallest |
