## ツールのインストール

以下のものをインストールしておく

- `VSCode`
    - `ms-vscode-remote.remote-containers`(Extension)
- `Docker`
- `git`

## 開発環境の起動

1. dockerを起動する

2. コードをcloneし、vscodeで開く

    ``` zsh
    git clone https://github.com/fujiwaki/serverless_hands_on.git
    code serverless_hands_on
    ```

3. 開発用コンテナで開く

    コマンドパレットを開く(Ctrl+Shift+P)

    `Dev Containers: Rebuild and Reopen in Container`を選択

4. ライブラリをインストールする

    ```zsh
    rye sync
    ```
