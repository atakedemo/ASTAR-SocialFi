セットアップなどのメモ
1. 環境構築
    * 構築する環境：Rust、Rustを使ったASTAR環境
    * コマンド系のメモ
      * ローカルノードの起動
       ```
      ./astar-collator --dev
        ```
      * X 
3. コントラクトの開発（astar_sns_contract 配下）
    * 使用する環境：Rust
    * ディレクトリ構造 
    * コマンド系のメモ
      * テストの実行 
        ```
        cargo +nightly-2022-08-15 test --nocapture
        ```
    * 
5. フロントエンドの構築（astar-sns-frontend 配下）
    * 使用する環境：Typescript 
    * ディレクトリ構造
    * コマンド系のメモ
      * Reactの基本ライブラリのインストール
      ```
      npm install react-icons --save
      npm i --save-dev @types/react-modal
      ```
      * 環境変数の設定（/pages に.envを配置）
      * Polkadot接続用のライブラリインストール
      ```
      npm install @polkadot/api @polkadot/extension-inject @polkadot/extension-dapp  
      npm install @polkadot/api-contract
      ```
      * 
    * X

7. その他