# Election DApp

## Dependencies

| Dependency | Version                                                                     |
| ---------- | --------------------------------------------------------------------------- |
| Metamask   | [0.6.1](https://github.com/MetaMask/metamask-extension/releases/tag/v6.1.0) |
| Node       | v11.0.0                                                                     |

## Steps

1. To install the dependencies.

```js
npm install
```

2. Ensure that a local blockchain instance is running(like Ganache) or run using

```sh
npm run ganache-cli
```

3. To compile the contracts.

```js
npm run compile
```

4. To deploy the contracts.

```js
npm run migrate
```

5. Log in to metamask on browser using mnemonic

```text
pig skull wine supply april fluid thing emerge pistol crucial crush cactus
```

6.To start the application

```js
npm run dev
```
