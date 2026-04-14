# Type: UserRating

**Category**: Available types

**Description**: This object describes the rating of a user based on their Telegram Star spendings.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#userrating)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| level | Integer | Yes | Current level of the user, indicating their reliability when purchasing digital goods and services. A higher level suggests a more trustworthy customer; a negative level is likely reason for concern. |
| rating | Integer | Yes | Numerical value of the user's rating; the higher the rating, the better |
| current_level_rating | Integer | Yes | The rating value required to get the current level |
| next_level_rating | Integer | Optional | Optional. The rating value required to get to the next level; omitted if the maximum level was reached |
