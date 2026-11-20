# Type: RichTextTonAddress

**Category**: Rich messages

**Description**: An address in the TON blockchain.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richtexttonaddress)

**Subtype of**: RichText

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the rich text, always "ton_address" |
| text | RichText | Yes | Text of the address |
| address | String | Yes | The address |
