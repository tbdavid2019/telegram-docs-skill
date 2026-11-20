# Type: WidgetQueryTypeSignData

**Category**: Available types

**Description**: The query contains data signed by a TON wallet of the user who sent the query. The data is signed for the domain bot<bot_id>, where <bot_id> is the identifier of the bot.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#widgetquerytypesigndata)

**Subtype of**: WidgetQueryType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the query, always "sign_data" |
| wallet | WidgetQueryWallet | Yes | The wallet that signed the data |
| sign_data | String | Yes | JSON-serialized signed data |
