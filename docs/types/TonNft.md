# Type: TonNft

**Category**: Available types

**Description**: This object represents an NFT in the TON blockchain.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#tonnft)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| address | String | Yes | Address of the NFT |
| collection_address | String | Optional | Optional. Address of the collection to which the NFT belongs; omitted if unknown |
| index | String | Yes | Index of the NFT among all NFTs from the collection as a decimal number |
| name | String | Yes | Name of the NFT |
| description | String | Yes | Description of the NFT |
| attributes | Array of TonNftAttribute | Optional | Optional. Attributes of the NFT |
| gift | UniqueGift | Optional | Optional. The unique gift corresponding to the NFT |
