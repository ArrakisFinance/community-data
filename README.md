# vaults-whitelist
Arrakis whitelist of Vaults

## Instructions to add a new vault to the whitelist

* Create a vault.
* Add your vault information to `whitelist.json` in the following format.
```
{
  "name": "Arrakis Vault V1 WMATIC/WETH",
  "address": "0xdc0eca1d69ab51c2b2171c870a1506499081da5b",
  "chainId": 137,
  "gauge": "0xEdF8C3aD1186d6ecB8b8cd08230b9434768252A5"
},
```
* Create a PR to the repository.