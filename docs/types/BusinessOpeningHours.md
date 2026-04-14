# Type: BusinessOpeningHours

**Category**: Available types

**Description**: Describes the opening hours of a business.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#businessopeninghours)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| time_zone_name | String | Yes | Unique name of the time zone for which the opening hours are defined |
| opening_hours | Array of BusinessOpeningHoursInterval | Yes | List of time intervals describing business opening hours |
