# MontMarie
Architecture proposal for mobile blockchain like data storage

## Proposed Spec - Rev 190322 2249 - v0.01d

This specification is focused on:

* Server-less (but can integrate some of them, if required)
* Distributed / descentralized data
* Modular / pluggable 
* Based on Blockchain / ethereum (not inter connected with them)
* Mobile focused
    * Low processing power
    * Medium data footprint
    * Small peers pool by device
* Value in blocks, not in mining: without cryptocurrency / cryptocoin (at least, not in the initial concept)
    * Low mining difficulty
    * Fast block integration
* Private blockchain: an app can have a single or multiple (like files) blockchains
    * Magnet-like invitations
    * medium size networks
* Encrypted communications
    * Multi protocol: webrtc, udp, tcp

**Note: this spec be in constant change until future notice (until the model convergence of 3 case apps)**

The expected initial implementation of modules will be for: javascript / typescript, scala and swift

### Node/peer (arch)types

* App / peer
* Data audit (server)
* Bridge (server)
* Bootstrap (server)

### Data modes

The initial proposal consist of 3 kind of states:

* App state
* Data state
* Accounts state

With 2 data modes

* Sum Delta / MoMa mode: based on the concept of I,P & B frames of mp4, where the equivalent I frame (MO block) will have the full state
* Blockchain mode: as currently (2018) is working - the sum of all blocks is the state

As most of the ledgers are working like the last, it will have low priority

## Suggested economic model

## Usage / example concepts

## License

Mpl 2.0

## Author

Gonzalo Covarrubias

## Motivation
