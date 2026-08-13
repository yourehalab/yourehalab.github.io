# Google Search Console 公開後チェックリスト

Search Consoleへの登録とインデックス申請は、SEOファイルをGitHub Pagesへ公開した後に行います。

## 1. サイトを登録する

1. [Google Search Console](https://search.google.com/search-console/)を開く。
2. 「プロパティを追加」を選ぶ。
3. 「URLプレフィックス」に `https://yourehalab.github.io/` を入力する。
4. 「HTMLファイル」で所有権を確認する場合は、Googleからダウンロードした `googleXXXXXXXX.html` をこのサイトの最上位フォルダに追加して公開する。
5. 公開後、Search Consoleへ戻って「確認」を押す。

`github.io` 全体のDNSは所有していないため、このサイトでは「ドメイン」ではなく「URLプレフィックス」を使用します。Googleが発行する確認ファイルは固有のものなので、ファイル名や中身を変更しないでください。

## 2. sitemap.xmlを送信する

1. 左メニューの「サイトマップ」を開く。
2. 「新しいサイトマップの追加」に `sitemap.xml` と入力する。
3. 「送信」を押し、ステータスが「成功しました」になることを確認する。

送信するサイトマップのURLは `https://yourehalab.github.io/sitemap.xml` です。

## 3. 3ページをインデックス申請する

以下を1件ずつ、上部の「URL検査」に貼り付けます。

- `https://yourehalab.github.io/`
- `https://yourehalab.github.io/biography.html`
- `https://yourehalab.github.io/publications.html`

各URLで「公開URLをテスト」を実行し、「URLはGoogleに登録できます」と表示されたら「インデックス登録をリクエスト」を押します。

## 4. 公開後に確認するもの

- `https://yourehalab.github.io/robots.txt` が表示される。
- `https://yourehalab.github.io/sitemap.xml` が表示される。
- URL検査で「インデックス登録を許可」が「はい」になる。
- URL検査に表示される「ユーザーが指定した正規URL」が、検査中のURLと一致する。
- 数日後、Search Consoleの「ページ」レポートで登録状況を確認する。

インデックス登録のリクエストやサイトマップ送信は、Googleへの登録を保証するものではありません。処理には数日以上かかることがあります。
