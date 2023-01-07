
![disney-plus](https://user-images.githubusercontent.com/103621682/211145362-eaef93bc-8b4f-45d5-8b93-5bd86a8908df.jpg)
![animated](https://user-images.githubusercontent.com/103621682/211145427-e6087434-d7ea-48b8-837b-0b610be67412.jpg)
![wild-animals](https://user-images.githubusercontent.com/103621682/211144989-b4cb5839-af47-4573-a5ce-ab0b3a43a6d6.jpg)
![naruto-shippuden-4k-anime-phone-hyvh21t6965i7w99](https://user-images.githubusercontent.com/103621682/211145656-0565b0d4-a8a2-4fdb-805c-968d8445c752.jpg)
![we-bare-bears-surfing-the-net-eh3w41yu8cqs0a44](https://user-images.githubusercontent.com/103621682/211145531-d814bab2-7c7f-46af-b9e6-9a590e38b5be.jpg)































# Hello Frontend

<img align="center" src='https://user-images.githubusercontent.com/103621682/211145609-e164f393-9eb5-4ec7-9d4c-7e9dc22cee44.png'></img>

This project contains the main features of the pancake application.

If you want to contribute, please refer to the [contributing guidelines](./CONTRIBUTING.md) of this project.

## Documentation

- [Info](doc/Info.md)
- [Cypress tests](doc/Cypress.md)

> Install dependencies using **yarn**

## `apps/web`
<details>
<summary>
How to start
</summary>

```sh
yarn
```

start the development server
```sh
yarn dev
```

build with production mode
```sh
yarn build

# start the application after build
yarn start
```
</details>

## `apps/aptos`
<details>
<summary>
How to start
</summary>

```sh
yarn dev:aptos
```
```sh
yarn turbo run build --filter=aptos-web
```
</details>


## Packages

| Package                                                       | Description                                                                                                            |
|---------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| [sdk](/packages/swap-sdk)                                     | An SDK for building applications on top of Pancakeswap                                                                 |
| [aptos-swap-sdk](/packages/aptos-swap-sdk)                    | Aptos version of Swap SDK                                                                                              |
| [swap-sdk-core](/packages/swap-sdk-core)                      | Swap SDK Shared code                                                                                                   |
| [wagmi](/packages/wagmi)                                      | Extension for [wagmi](https://github.com/wagmi-dev/wagmi), including bsc chain and binance wallet connector            |
| [awgmi](/packages/awgmi)                                      | connect to Aptos with similar wagmi React hooks.                                                                       |

