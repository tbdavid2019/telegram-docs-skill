# Type: WidgetQueryWallet

**Category**: Available types

**Description**: This object describes a TON wallet of the user, which is used in a query from a widget.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#widgetquerywallet)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| address | String | Yes | Address of the wallet |
| amount | String | Yes | Balance of the wallet, in the smallest units of the cryptocurrency, as a decimal number |
| public_key | String | Optional | Optional. Hex-encoded public key of the wallet; omitted if unknown |
| state_init | String | Optional | Optional. Base64-encoded serialized StateInit of the wallet contract; omitted if and only if public_key is omitted |
