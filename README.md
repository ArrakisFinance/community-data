# community-data
Arrakis static data for all community vaults

## Instructions to add a new vault to the vaultsList

* Create a vault.
* Add your vault information to `vaultsList.json` in the following format.
```
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

** note: if there is no liquidity gauge, simply put "gauge": null
```
* Create a PR to the repository.