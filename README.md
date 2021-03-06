# Aragon React Kit Boilerplate

> 🕵️ [Find more boilerplates using GitHub](https://github.com/search?q=topic:aragon-boilerplate) | 
> ✨ [Official boilerplates](https://github.com/search?q=topic:aragon-boilerplate+org:aragon)

React boilerplate for Aragon applications.

This boilerplate also includes a fully working example app, complete with a background worker and a front-end in React (with Aragon UI).

## Usage

Kit support requires using the Aragon CLI 4.1.0 beta versions.
```sh
npm install -g @aragon/cli@beta
aragon init app aragon/aragon-react-kit-boilerplate
```

## Run the kit

```sh
aragon run --kit Kit --kit-init @ARAGON_ENS
```

## Prerequisites

- [**truffle**](https://github.com/trufflesuite/truffle): Used to build and test the contracts

## What's in the box?

### npm Scripts

- **start**: Run the app locally
- **compile**: Compile the smart contracts
- **build**: Compiles the contracts and builds the front-end
- **test**: Runs tests for the contracts
- **publish**: Builds the apps and the contracts and publishes them to IPFS and APM

### Libraries

- [**@aragon/os**](https://github.com/aragon/aragonos): Aragon interfaces
- [**@aragon/client**](https://github.com/aragon/aragon.js/tree/master/packages/aragon-client): Wrapper for Aragon application RPC
- [**@aragon/ui**](https://github.com/aragon/aragon-ui): Aragon UI components (in React)
