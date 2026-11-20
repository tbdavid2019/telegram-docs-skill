# Type: WidgetQueryTypeData

**Category**: Available types

**Description**: The query contains data for the bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#widgetquerytypedata)

**Subtype of**: WidgetQueryType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the query, always "data" |
| wallet_card | TonWalletCard | Optional | Optional. TON wallet card of the user who sent the query, if it was sent to the bot along with the query |
