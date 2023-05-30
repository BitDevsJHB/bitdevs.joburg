---
layout: post
type: socratic
title: "Socratic Seminar 1"
meetup: "https://www.meetup.com/BitDevsJHB/293857566"
---

## Announcements

Please join us for the first BitDevs Joburg Socratic Seminar!

Thanks to ThunderPunch ⚡👊 for sponsoring the venue and snacks 🍕❤️

## Presentation

- Welcome to BitDevs Joburg - [@dunxen](https://github.com/dunxen)

## Mailing Lists, Meetings and Bitcoin Optech

### Optech
- [Newsletter #252](https://bitcoinops.org/en/newsletters/2023/05/24/)

## Pull Requests and repo updates

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [LDK #2204](https://github.com/lightningdevkit/rust-lightning/issues/2204) adds the ability to set custom feature bits for announcing to peers,
  or for use when attempting to parse a peer’s announcement.
- [LDK #1794](https://github.com/lightningdevkit/rust-lightning/issues/1794) begins adding support for dual funding, starting with methods needed
  for the interactive funding protocol that is used for dual funding.

## New Releases
- [Bitcoin Core 25.0](https://bitcoincore.org/en/releases/25.0/)
  - **P2P and network changes**: Mempool policy is loosened to allow for transactions of non-witness size 65 bytes (previously 82 bytes) and above
    to be considered standard and propagated by nodes.

## Miscellaneous
- [Route blinding](https://github.com/lightning/bolts/blob/master/04-onion-routing.md#route-blinding) - Better privacy for recipients on the Lightning Network.
- [Schnorr signatures](https://bitcoinops.org/en/topics/schnorr-signatures/) - New (old) kid on the _block_.
- [ECDSA signatures](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm) - Why they were created and why they're weird. 
- [Discreet Log Contracts](https://bitcoinops.org/en/topics/discreet-log-contracts/) - Spelling, how schnorr makes them possible (easier), and use cases.
- [BIP 39](https://bips.xyz/39) - Shallow dive, criticisms, and why the Bitcoin Core wallet still doesn't support it.
