# Type: BusinessOpeningHoursInterval

**Category**: Available types

**Description**: Describes an interval of time during which a business is open.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#businessopeninghoursinterval)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| opening_minute | Integer | Yes | The minute's sequence number in a week, starting on Monday, marking the start of the time interval during which the business is open; 0 - 7 * 24 * 60 |
| closing_minute | Integer | Yes | The minute's sequence number in a week, starting on Monday, marking the end of the time interval during which the business is open; 0 - 8 * 24 * 60 |
