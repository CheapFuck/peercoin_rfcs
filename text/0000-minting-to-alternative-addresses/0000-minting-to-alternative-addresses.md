# Minting To Alternative Addresses

- Status: proposed
- Type: new feature, enhancement
- Start Date: 23-03-2024
- Discussion: (fill me in with link to RFC discussion - shepherd will complete this) 
- Supersedes: na
- Superseded by: na
- Author: CheapFuck

## Summary

Add the feature to receive mint rewards to new/alternative addresses. Specifying a certain address, or new addresses (from the key pool).

## Conventions
- The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](http://tools.ietf.org/html/rfc2119).

## Motivation

Improved privacy. 

## Detailed design

Users can specify an address that will be used for receiving mint rewards. This can be custom valid address, or a new address every time a proof of stake block is minted.

## Drawbacks

Potential drawbacks could be, the new address that receives the mint reward could take a long time before it mints, this could be addressed by "pooled" minting.
The need to make back-ups more often, when the key-pool has been exhausted, could be addressed by increasing the key-pool size.

## Alternatives

## Unresolved questions

