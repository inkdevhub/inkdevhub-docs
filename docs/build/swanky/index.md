import Figure from "/src/components/figure"


# Swanky Suite 

Swanky Suite aims to be an "all-in-one" tool for Wasm smart contract developers. It is based on existing tools like `cargo contract CLI` and `polkadot.js` but extends their functionality with many additional features such as smart contract templates, and an instant finality (Swanky) node, which reduces the contract development lifecycle.

 <Figure caption="Build" src={require('../img/astar-swanky.jpg').default } width="100%" /> 

Swanky Suite is a tool that provides Web3 Wasm dapps developers with an experience that is more in-line with what they're familiar with, compared to popular tooling for EVM.

Swanky Suite offers an extensible set of features, allowing developers to:

- Quickly spin up a local contract development node with instant finality (Swanky Node);
- Provide a ready dev environment via prebuilt Docker image and dev-container configuration;
- Easily scaffold new projects using templates for both smart contracts and (soon) front-end dApps;
- Compile ink! projects and generate TS types;
- Provide Typescript based integration testing simulating interaction from the client-side;
- Handle and manage network accounts;
- Deploy smart contracts within the Polkadot ecosystem to networks that support `pallet-contracts`;
- Make arbitrary calls to deployed smart contracts.

## Architecture Overview

The Swanky Suite consists of three parts, Swanky CLI, Swanky Node, and the Docker image (Dockerfile is in the swanky-cli repo, and the built image is hosted on github.

Source code for both Swanky CLI and Swanky Node are hosted on GitHub:

- Swanky CLI
- Swanky Node 

## Documentation and resources

This documentation's sub-sections on usage of Swanky CLI and Swanky Node have great instructions on how to setup the tool and start using it right away.

`swanky` CLI Github repo with the latest releases, ink! Dev Hub documentation;

`swanky-node` Github repo with the latest releases, ink! Dev Hub documentation;

`pallet-contracts` documentation on Parity Github;

[ink! language](https://github.com/paritytech/ink) repo and specification.
