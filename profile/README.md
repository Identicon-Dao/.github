# Identicon DAO

A DAO for managing the `identicon.network` and it's protocol.

## Briefing

`Identicon.network` is a trustless protocol for identity verification in the NEAR network, focused on providing multiple signed verifications of a real world entity and binding it to one (or more) digital identities, and independent of the form these digital identities may take (NFT, DID, etc).  It is not an identity vault or a repo for unique identity. 

Is based on a set of decentralized and random selection of human nodes (citizens) which will produce the “on-site” verification of the solicited identity,  proof of life or proof of existence.

Typical use cases are "proof of life", "proof of identity" or "proof of anything" for “real people” in the NEAR network. 

**Authors**

- Mario A. Zito (mazito.v2@gmail.com, @MAZ)
- Leandro Manzanal (leomanzanal@gmail.com, @LM)

**Changelog:**

- Feb 14 2022 - @MAZ - preliminar doc of proof of life service run by a DAO
- Feb 23 2022 - @LM - reviewed, commented, Web3 terminology
- Mar 11 2022 - @MAZ - presented as Identicon.network (NCA project)
- Mar 18 2022 - @LM, @MAZ - reformulated as a verification protocol

## Features:

- Binds trusted real world identity to one (or more) unique digital identities.
- Puts validation in the hands of the people (citizen verification). Anyone can be a validator. 
- Takes validation to the place where people live, not forcing people to move to some central place to prove their identity.
- Simplifies proof of identity requests and validation process on an intuitive and easy to use Dapp.
- Allows recurrent validations (once a week, once a month, etc) to be scheduled and managed by the network.

Opens a whole set of use cases:

- validating the existence of physical assets
- validating providers of goods and services. 
- proving identity and life for validated users on social media platforms.
- implementing KYC for Defi or regulated accounts

## Why

The "digital interface" between us and the real world implies that in many cases we really don't know who we are interacting with. Is this person who he/she says he/she is ? Is he/she a fake ? Is he/she alive ?

This lack of knowledge has also a whole set of implications in the OpenWeb, such as knowing and identifying contributors, clients, avoiding rug pull and scams. The list of frauds increases day by day allowed by the lack of identity on projects and the people who operate them.

We think that solving this problem provides anticipated social and identity fraud detection, preserving reputations, generating huge savings in lost funds, and avoiding many other social and economic losses.

It also opens a whole set of use cases where these validated identities can be safely used, with deep social and economic impacts.

There have been various approaches in the Web3 community for solving this, we mention five here:

- Self-sovereign identity (en.wikipedia.org/wiki/Self-sovereign_identity)
- Bright ID (www.brightid.org): Identity is a human right. BrightID is a social identity network that allows you to prove that you’re only using one account. It’s the holy grail of digital identity.
- Proof of Humanity (www.proofofhumanity.id): a system combining webs of trust, with reverse Turing tests, and dispute resolution to create a sybil-proof list of humans.
- DIDI (didi.org.ar): Blockchain para una identidad digital auto-soberana.
- DID (https://www.did.id/) - aka DAS Decentralized Account System.

But we think that the current implementations present problems that made them ineffective, or not fully “trustless”:

- Relies on having to ask people you know to vouch for you, which allows fraud schemas and also is not viable for a whole set of people (ProofOfHumanity)
- Rely on government or authoritative institutions for validation (such as RENAPER), with the known centralizing effects (DIDI)
- Complex to use for inexperienced users requiring to have a wallet, have some crypto funds in them, send funds, etc.
- Inability for older people to use them, when they will be one of the main requestors of validation, due to the low digital culture and low level access to technology.
- No fiat transactions: Difficult to pay validation requests and validator compensations in fiat currency, though this may be solved when more wallets allow fiat interactions. 
- Focused on the unique identity, but not on the identity verification process (BrightID).
- Expensive: High transaction costs and gas fees for operation.

And even when some of this aspects are being considered or corrected in some implementations, we think that our approach to verification using citizen “nodes” presents benefits over existent solutions:

- Decentralization: use of random citizen validators assures effective decentralization, without allowing any authoritative or central organization to take control. As a protocol, multiple DAOs can act as validations services providers using the protocol.

- Extra transparency: the use of random and unknown validators, as well as additional eventual random auditors, provide extra transparency to the protocol.

- Ease of use: allowing the service to take care of all aspects of the validation process and taking the validations “on-site” by registered validators, greatly simplifies its adoption and use, transforming it into a service, rather than a complex do-it-yourself digital validation.

- Low cost: using NEAR network allows lower costs for the solicitant and better compensation for validators, a critical aspect for viability.

