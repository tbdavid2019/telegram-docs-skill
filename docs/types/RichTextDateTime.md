# Type: RichTextDateTime

**Category**: Rich messages

**Description**: Formatted date and time.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#richtextdatetime)

**Subtype of**: RichText

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the rich text, always "date_time" |
| text | RichText | Yes | The text |
| unix_time | Integer | Yes | The Unix time associated with the entity |
| date_time_format | String | Yes | The string that defines the formatting of the date and time. See date-time entity formatting for more details. |
