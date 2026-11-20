# Type: TonWalletCard

**Category**: Available types

**Description**: This object describes a TON wallet card, which is shown on the profile page of a user to everyone.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#tonwalletcard)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| address | String | Yes | Address of the wallet |
| amount | String | Yes | Balance of the wallet, in the smallest units of the cryptocurrency, as a decimal number |
| stickers | Array of TonWalletCardSticker | Yes | Stickers placed on the card |
| background_nft_address | String | Optional | Optional. Address of the NFT of one of the stickers, whose colors must be used for the card background; omitted if the default background must be used |
