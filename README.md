# Axolotl Swap Interface

An open source interface for Axolotl Swap -- a protocol for decentralized exchange of Ethereum tokens.

- Website: [axolotl.finance](https://axolotl.finance/)
- Interface: [swap.axolotl.finance](https://swap.axolotl.finance)
- Twitter: [@AxolotlToken](https://twitter.com/AxolotlToken)
- Reddit: [/r/AxolotlToken](https://www.reddit.com/r/AxolotlToken/)
- Email: [hello@axolotl.finance](mailto:hello@axolotl.finance)
<!-- - Discord: [Uniswap](https://discord.gg/FCfyBSbCU5) -->
- Whitepaper: [Link](https://axolotl.finance/WhitePaperAxolotl.pdf)
 
 
## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"`

Note that the interface only works on testnets where both
[Uniswap V2](https://uniswap.org/docs/v2/smart-contracts/factory/) and
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Contributions

**Please open all pull requests against the `main` branch.**
CI checks will run against all PRs.
