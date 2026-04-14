# Type: InputInvoiceMessageContent

**Category**: Inline mode

**Description**: Represents the content of an invoice message to be sent as the result of an inline query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#inputinvoicemessagecontent)

**Subtype of**: InputMessageContent

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| title | String | Yes | Product name, 1-32 characters |
| description | String | Yes | Product description, 1-255 characters |
| payload | String | Yes | Bot-defined invoice payload, 1-128 bytes. This will not be displayed to the user, use it for your internal processes. |
| provider_token | String | Optional | Optional. Payment provider token, obtained via @BotFather. Pass an empty string for payments in Telegram Stars. |
| currency | String | Yes | Three-letter ISO 4217 currency code, see more on currencies. Pass "XTR" for payments in Telegram Stars. |
| prices | Array of LabeledPrice | Yes | Price breakdown, a JSON-serialized list of components (e.g. product price, tax, discount, delivery cost, delivery tax, bonus, etc.). Must contain exactly one item for payments in Telegram Stars. |
| max_tip_amount | Integer | Optional | Optional. The maximum accepted amount for tips in the smallest units of the currency (integer, not float/double). For example, for a maximum tip of US$ 1.45 pass max_tip_amount = 145. See the exp parameter in currencies.json, it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). Defaults to 0. Not supported for payments in Telegram Stars. |
| suggested_tip_amounts | Array of Integer | Optional | Optional. A JSON-serialized array of suggested amounts of tip in the smallest units of the currency (integer, not float/double). At most 4 suggested tip amounts can be specified. The suggested tip amounts must be positive, passed in a strictly increased order and must not exceed max_tip_amount. |
| provider_data | String | Optional | Optional. A JSON-serialized object for data about the invoice, which will be shared with the payment provider. A detailed description of the required fields should be provided by the payment provider. |
| photo_url | String | Optional | Optional. URL of the product photo for the invoice. Can be a photo of the goods or a marketing image for a service. |
| photo_size | Integer | Optional | Optional. Photo size in bytes |
| photo_width | Integer | Optional | Optional. Photo width |
| photo_height | Integer | Optional | Optional. Photo height |
| need_name | Boolean | Optional | Optional. Pass True if you require the user's full name to complete the order. Ignored for payments in Telegram Stars. |
| need_phone_number | Boolean | Optional | Optional. Pass True if you require the user's phone number to complete the order. Ignored for payments in Telegram Stars. |
| need_email | Boolean | Optional | Optional. Pass True if you require the user's email address to complete the order. Ignored for payments in Telegram Stars. |
| need_shipping_address | Boolean | Optional | Optional. Pass True if you require the user's shipping address to complete the order. Ignored for payments in Telegram Stars. |
| send_phone_number_to_provider | Boolean | Optional | Optional. Pass True if the user's phone number should be sent to the provider. Ignored for payments in Telegram Stars. |
| send_email_to_provider | Boolean | Optional | Optional. Pass True if the user's email address should be sent to the provider. Ignored for payments in Telegram Stars. |
| is_flexible | Boolean | Optional | Optional. Pass True if the final price depends on the shipping method. Ignored for payments in Telegram Stars. |
