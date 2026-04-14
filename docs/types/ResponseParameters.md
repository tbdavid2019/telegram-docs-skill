# Type: ResponseParameters

**Category**: Available types

**Description**: Describes why a request was unsuccessful.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#responseparameters)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| migrate_to_chat_id | Integer | Optional | Optional. The group has been migrated to a supergroup with the specified identifier. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. |
| retry_after | Integer | Optional | Optional. In case of exceeding flood control, the number of seconds left to wait before the request can be repeated |
