# Voice Test

音声で会話しながらウェブサイトを作成し、Gitで変更を記録するための小さな開発テストです。
日本語の紹介ページをHTMLとCSSだけで構成しています。ページ自体に録音・音声認識機能はありません。

## 起動方法

`index.html`をブラウザで開くだけで表示できます。ビルドや依存パッケージのインストールは不要です。

ローカルHTTPサーバーを利用する場合は、Python 3が入っている環境で次を実行します。

```sh
cd voice-test-website
python3 -m http.server 8000 --bind 127.0.0.1
```

ブラウザで <http://127.0.0.1:8000> を開きます。サーバーの停止は `Ctrl+C` です。

## ファイル構成

- `index.html`: 紹介文と開発の流れ
- `style.css`: レイアウト、配色、スマートフォン向け表示

## 確認すること

- ページとスタイルが読み込まれること
- 「開発の流れを見る」から該当セクションに移動できること
- スマートフォン幅でも横にはみ出さず読めること
- キーボードのTabキーでリンクにフォーカスできること

## リモートへの保存

クローンしたリポジトリでは、変更をコミットしてプッシュします。

```sh
git push -u origin codex/voice-test-website
```

GitHub Pagesは `codex/voice-test-website` ブランチのルートから公開します。

公開URL: <https://masaaki-hamada-id.github.io/voice-test-website/>
