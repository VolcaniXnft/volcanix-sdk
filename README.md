# @volcanix/sdk - v1.0.0

This SDK is a collection of tools used to interact with the Volcanix API and smart contracts.

## Usage

### Install

Install with

```bash
yarn add @volcanix/sdk 
```

or

```bash
npm install @volcanix/sdk --save
```

### Documentation

Read the [complete documentation](./doc/index.md)

## Dev

### Setup

Install dependencies with `yarn`

- **Dev**: `yarn dev`
- **Build**: `yarn build`

### Release
- Create an `.env` (copy `.env.template`) and set you github personal access token.
- `yarn release` will run all the checks, build, and publish the package, and publish the github release note.
