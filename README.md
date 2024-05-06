# 概要

第6回課題の内容は下記の通り。

1. Spring Bootを使って画面にHello Worldを表示。
2. Hello Worldを表示したプロジェクトに自分で考えた変更を加える。
    - 変更は新しいブランチにコミットしてGitHubにpushし、GitHub上でPRする。

今回の実装内容は、`localhost:8080/hello`へアクセスしたら「`Hello World`」を返すというmainブランチに対し、`localhost:8080/hellotime`
へアクセスしたら「`Hello World`と現在時刻」をJSON形式で返すように、新しいブランチにcommitした。  

下の画像は、`localhost:8080/hello`へアクセスしたら「`Hello World`」を返す、に対するPostmanを使用した動作確認結果。

![image](https://github.com/Ema-Sakai/Assignment-6/assets/166620990/8a527950-6844-4a9e-abcf-6802f6f50462)


良しとした理由は、下記のとおりです。
- レスポンスボディが Hello World である。
- レスポンスのステータスコードが 200 である。
