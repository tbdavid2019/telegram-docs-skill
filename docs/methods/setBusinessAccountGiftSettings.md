# Method: setBusinessAccountGiftSettings

**Category**: Available methods

**Description**: Changes the privacy settings pertaining to incoming gifts in a managed business account. Requires the can_change_gift_settings business bot right. Returns True on success.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#setbusinessaccountgiftsettings)

**Returns**: Boolean

### Parameters

| Field | Type | Required | Description |
|---|---|---|---|
| business_connection_id | String | Yes | Unique identifier of the business connection |
| show_gift_button | Boolean | Yes | Pass True, if a button for sending a gift to the user or by the business account must always be shown in the input field |
| accepted_gift_types | AcceptedGiftTypes | Yes | Types of gifts accepted by the business account |
