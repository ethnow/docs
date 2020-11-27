# ethnow - The Ethereum integration for ServiceNow

ethnow aims to create a production-ready Ethereum spoke for ServiceNow. All modules can operate in a totally self-contained way withing the ServiceNow instance, without the need of any external component, including the MID server.

The project contains the following repositories:
- ethsign. A signer based on the ServiceNow platform.
- ethspoke. The Ethereum spoke, that used ethsign to sign transaction and to provision cryptographic key pairs to ServiceNow users
- nowtoken. An example application that is based on ethnow and that implement a token NOW that can be exchanged within and across customer instances.

## Description

The ethnow project uses the primitives provided by the [ethjs](https://github.com/ethjs) project.

The following libraries have been adapted/polyfilled to the ServiceNow javascript engine (Rhino) and embedded in the applications as script include:

| Library | Purpose |
|---|---|
|ethjs-signer| Sign Ethereum transactions|
|ethjs-account| Generate key pairs and manage accounts|
|ethjs-abi| Encoding and decoding utilities|
|ethjs-format| Payload formatter for the Ethereum RPC layer |
|---|---|

The ethnow spoke talk with the Ethereum node(s) through the node JSON-RPC API.

## How to install 




## How to use


## How to contribute





