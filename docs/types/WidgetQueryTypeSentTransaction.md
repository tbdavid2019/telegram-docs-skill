# Type: WidgetQueryTypeSentTransaction

**Category**: Available types

**Description**: The query notifies the bot about a transaction sent from a TON wallet of the user who sent the query.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#widgetquerytypesenttransaction)

**Subtype of**: WidgetQueryType

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the query, always "sent_transaction" |
| wallet | WidgetQueryWallet | Yes | The wallet from which the transaction was sent |
| msg_hash | String | Yes | Value of msg_hash of the transaction |
