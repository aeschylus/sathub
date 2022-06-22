# sathub
A drop-in bank for every website.

## Background
The lightning network allows technical users with significant Bitcoin liquidity to facilitate fast and cheap transfers anywhere in the world. However, it is currently not practical for non-technical users to personally provide themselves with the privacy and anonymity guarantees of node ownership. Furthermore, for many applciations, the lightning network is actually too slow. Without some degree of credit risk, truly immediate payments, such as those required by retail purchases and streaming digital payments in virtual economies, are not reliably possible over the lightning network. Chaumian Mints provide extremely strong privacy and liquidity and latency guarantees for the sacrifice of some custodial risk. [Federated Chaumian Mints](https://fedimint.org/) further mitigate aspects of this custodial risk. One future for Bitcoin, and everyday users of money online, may be a _federation **of**_ federated chaumian mints communicating over the lightning network, operated by a variety of service companies, including websites and web applications.

Just as MMORPGs can mitigate latency by using powerful, centralised systems to synchronise game state for millions of users, in order to maintain an experience of immediacy for users while removing risks associated with short-term credit that would otherwise be required, a locally-centralised liquidity and payments infrastructure makes sense for a large swathe of applications. Blind tokens representing satoshis are interoperable between mints, which settle with each other over well-provisioned lightning nodes such as can be operated by teams running an existing web service.

## Architecture
A **sathub** is a drop-in bank for every website. It consists of a Bitcoin full node, a well-provisioned Lightning Network node, and a Federated Chaumian Mint whose tokens are interoperable with other sathubs. Together, many Sathubs comprise a federation of Federated Chaumian Mints whose tokens are interoperable with one another. This allows any pegging in and pegging out that may occur between mints to take place over the lightning network at a mildly increased latency, providing the illusion of immediate settlement with extremely low cost, credit risk, and final settlement time.

### The Bitcoin Collateral Core
### The Lightning Node
### The Mint
### Blind Satoshis Standardisation
### The Inter-hub Settlement API
#### Checking if a token is valid
#### Requesting Peg-in for a token
### The User-facing API
#### Payment
#### Accounts
#### Wallet
