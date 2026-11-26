# ドイツ語 到達度診断 (PWA)

## 公開(GitHub Pages)
1. GitHubで新しい公開リポジトリを作る(例: de-diag)。
2. このフォルダの中身(index.html, sw.js, manifest.webmanifest, icon-*.png)をそのままリポジトリ直下にアップロードする。
3. Settings > Pages > Branch を main / (root) にして保存。
4. 数分後に https://<ユーザー名>.github.io/de-diag/ で開ける。

## iPadへの追加
1. Safariで上のURLを開く(iPadではSafariから追加するのが確実)。
2. 共有ボタン > 「ホーム画面に追加」。
3. 一度オンラインで開けば、以降は機内モードでも動く。

## 更新するとき
index.html を差し替え、sw.js の先頭の V="de-diag-v1" を v2, v3 と上げてからアップロードする。
