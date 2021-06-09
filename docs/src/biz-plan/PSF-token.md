# PSF Token

The PSF token is a utility token. It has two primary purposes:

- Unlock token-only services and discounts.
- Allow members to participate in governance of the PSF organization.

## Token Services and Discounts

Much of the software infrastructure maintained by the PSF focuses on the software as a service (SaaS) business model, as that model lends itself best to the use of utility tokens. The use of SaaS software by end-users imbues the token with financial value. Many ideas are borrowed from the [Bancor whitepaper](https://github.com/Permissionless-Software-Foundation/token-liquidity/blob/master/docs/bancor-formulas/bancor-protocol-whitepaper.pdf), such as the concepts of token liquidity and forming a community that can self-fund through a local currency (token). See [this video](https://youtu.be/LcbHTF3zCdI) for additional background. The primary purpose of the token is to fund developers and other contributors, in order to maintain and improve the SaaS software produced by the Foundation.

When end-users pay for software services, the cryptocurrency they pay goes to burn tokens, and the cryptocurrency is captured in a special [token-liquidity application](https://github.com/Permissionless-Software-Foundation/token-liquidity) (inspired by the [Bancor whitepaper](https://github.com/Permissionless-Software-Foundation/token-liquidity/blob/master/docs/bancor-formulas/bancor-protocol-whitepaper.pdf)). The cryptocurrency acts as a reserve asset, backing the value of the token. The price of the token is pegged to its reserve asset through by a math equation. This also provides perfect liquidity for the PSF token, since it can always be traded for the cryptocurrency backing it. Research, development, and maintenance are funded via token-grants, by existing token holders. The token-liquidity application allows contributors to exchange their tokens for the underlying cryptocurrency.

![Circular Token Economy](./media/circular-economy.png)

New tokens are minted to fund developers (supply), and old tokens are taken out of circulation through the burning mechanism of users consuming services (demand). New tokens are directed by existing token holders to fund developer grants every three months. It is the responsibility of PSF token holders (participating the in the governance of the organization) to balance the circulating supply and price of the token.
