# Type: ShippingQuery

**Category**: Payments

**Description**: This object contains information about an incoming shipping query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#shippingquery)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| id | String | Yes | Unique query identifier |
| from | User | Yes | User who sent the query |
| invoice_payload | String | Yes | Bot-specified invoice payload |
| shipping_address | ShippingAddress | Yes | User specified shipping address |
