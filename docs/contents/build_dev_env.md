# 開発環境構築

## ツールのインストール

以下のものをインストールしておく

- `VSCode`
    - Extensions
        - `ms-vscode-remote.remote-containers`
- `Docker`
- `git`

## 開発環境の構築

1. dockerを起動する

2. コードをcloneし、vscodeで開く

    ``` zsh
    git clone https://github.com/fujiwaki/serverless_hands_on.git
    code serverless_hands_on
    ```

3. devcontainerをbuildしcontainer環境で開く

    コマンドパレットを開く(Ctrl+Shift+P)

    Dev Containers: Rebuild and Reopen in Containerを選択

4. ライブラリをインストールする

    ```zsh
    rye sync
    ```
