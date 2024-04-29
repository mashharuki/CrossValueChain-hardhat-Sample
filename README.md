# CrossValueChain-hardhat-Sample

hardhatを使ったCrossValueChain検証用のリポジトリです。

## 動かし方

- インストール(コントラクト側)

  ```bash
  cd backend
  yarn
  ```

- 初期設定

  デプロイしたコントラクトのアドレス情報を保管するための json ファイルをネットワーク毎に作成する。

  すでにこの json ファイルが生成されている場合はこのコマンドを実行しないこと！！

  データがなくなります！！

  ```bash
  yarn reset --network kura
  ```

- デプロイ

  ```bash
  yarn deploy:kura
  ```

  デプロイしたコントラクト

  [Lock 0xa05Db9C31B6ffB6aB817D346E99095e1c1c8317D](https://testnet.crossvaluescan.com/address/0xa05Db9C31B6ffB6aB817D346E99095e1c1c8317D/contracts#address-tabs)

### 参考文献

1. [テストネット BlockExplorer](https://testnet.crossvaluescan.com/)
2. [Hardhat CrossValueChain Docs](https://docs.crossvalue.io/testnet/how-to-deploy-to-smart-contracts-hardhat)
