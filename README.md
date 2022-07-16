# Gatsby.js Authentication

**Basic認証の代替案**

**デプロイサイトリンク**

https://samplegatsbyauthmain.gatsbyjs.io/

**参考リンク**

https://www.gatsbyjs.com/tutorial/authentication-tutorial

## 🚀 Quick start

1.  **Install gatsby**
    ```shell
    npm install -g gatsby-cli
    ```

1. **Clone this repository**
    ```shell
    git clone https://github.com/ichizokichinosuke/sample-gatsby-auth.git
    ```

1.  **Start developing.**
    ```shell
    cd sample-gatsby-auth/
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

## 💫 Deploy

Gatsby Cloudにデプロイする。
以下のボタンをクリックし、会員登録した後に Add a site ボタンを押し、画面に表示されている指示に従う。
[<img src="https://www.gatsbyjs.com/deploynow.svg" alt="Deploy to Gatsby Cloud">](https://www.gatsbyjs.com/dashboard)

## サンプルコード

### 認証
[client-only routes](https://www.gatsbyjs.com/docs/how-to/routing/client-only-routes-and-user-authentication/)という概念を基に、ログイン済みのユーザとそうでないユーザに表示するコンテンツを区別するもの。

[公式ドキュメント](https://www.gatsbyjs.com/tutorial/authentication-tutorial)の手順通りに実装する。

以下のユーザネームとパスワードでログイン可能。

username: ken

password: pass


### 代替案2（未検証）
Gatsby．js公式リポジトリのIssueにて議論されていた、```onCreateDevServer``` を使う方法
https://github.com/gatsbyjs/gatsby/issues/24266
