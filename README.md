# vol.1

## Vue.js を使う目的とメリット

- 目的：JS でラクにアプリケーションを作成するため
- メリット：汎用的な（仕様変更に強い）設計ができる

### JavaScript を使う目的

- DOM を操作
- 非同期で HTTP 通信を行う（Ajax）

  👉 アプリケーションを作る

### JavaScript フレームワークとは

- JS でアプリケーションを制作する際の便利機能をパッケージしたもの

  👉 JS で書くと面倒なことも、すでに機能化されている

- フレームワークを使うことで、実装方法を共通化することができる

  👉  同じ要件に対して、同じ記述方法で統一することができる

### Vue.js とは

#### Vue.js 単体はテンプレートライブラリ

- 記述方法は HTML にマスタッシュやディレクティブを記述して使用する

  👉  学習コストが低い

- Vue.js でアプリを設計する際の考え方

  👉  データバインドで設計する

- Vue.js はコンポーネントで設計する

  👉  機能単位でコンポーネント化し、組み合わせて設計する

- アニメーション用の機能も持っている
- ルーターやストアシステムなどのモジュールを組み合わせることでフレームワークとなる

## Vue.js の設計パターン

- データにより View を操作する
- イベント発火時にデータを操作し、View を変える

  👉  **イベント → データ操作 → DOM 更新** （[参考](https://lab.aratana.jp/entry/2017/12/09/000000)）

## Hands-on Practice

実際に制作してみましょう！

### その前に

- エディター：[Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/) & Vue VS Code Extension Pack
- デバッガー：[Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=ja)