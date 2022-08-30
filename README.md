# Arrakis Community Data

Arrakis static data for all community vaults

## Adding a new vault

#### Add an entry to the `vaults` field of the `vaultsList.json` file in the following format:

```json
{
  "name": "Arrakis Vault V1 WMATIC/WETH",
  "address": "0xdc0eca1d69ab51c2b2171c870a1506499081da5b",
  "chainId": 137,
  "gauge": {
    "address": "0xEdF8C3aD1186d6ecB8b8cd08230b9434768252A5",
    "rewardToken": "0x0d500B1d8E8eF31E21C99d1Db9A6444d3ADf1270",
    "rewardLength": 608000
  }
}
```

**Note:** if there is no liquidity gauge, simply put `"gauge": null`

#### If required add new tokens to the `tokens` field of the `tokenlist.json` file in the following format:

```json
{
  "chainId": 1,
  "address": "0x15b7c0c907e4C6b9AdaAaabC300C08991D6CEA05",
  "decimals": 18,
  "name": "Gelato Network Token",
  "symbol": "GEL",
  "logoURI": "https://raw.githubusercontent.com/ArrakisFinance/arrakis-tokenlist/main/images/0x15b7c0c907e4C6b9AdaAaabC300C08991D6CEA05-1.svg"
}
```

**Note:** Use [checksum address](https://docs.ethers.io/v5/api/utils/address/#address) everywhere!

#### Open PR and make sure all checks passed ✨
