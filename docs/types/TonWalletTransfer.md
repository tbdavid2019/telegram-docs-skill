# Type: TonWalletTransfer

**Category**: Available types

**Description**: Describes a service message about a transfer with a TON wallet.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#tonwallettransfer)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| transaction_id | String | Yes | Unique identifier of the transaction; may be empty if the transfer hasn't been sent yet |
| peer_address | String | Yes | Address of the transfer peer in the TON blockchain |
| amount | String | Yes | The amount of transferred cryptocurrency, in the smallest units of the cryptocurrency, as a decimal number; negative for outgoing transfers |
| comment | String | Optional | Optional. Comment added to the transfer; omitted if the comment is encrypted |
