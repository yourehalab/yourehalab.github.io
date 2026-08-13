# Yu Kitaji Biography Site

北地雄 / Yu Kitaji のBiography・研究業績を掲載する静的Webサイトです。

## Design
- Modern academic / editorial design
- Responsive layout
- WCAGを意識した可視フォーカスと十分な操作領域
- Biographyでは長文の行長を制限し、Academic serviceをカード型で整理
- Publicationsでは検索・カテゴリ絞り込み・年別表示に対応

## Pages
- `index.html` — Home
- `biography.html` — Biography / About
- `publications.html` — Publications / Presentations
- `data.js` / `data.json` — 業績データ
- `styles.css` — デザイン
- `app.js` — ナビゲーション、検索・フィルタ
- `sitemap.xml` / `robots.txt` — 検索エンジン向けクロール設定
- `og-image.png` — SNS共有時に表示するOGP画像（1200×630px）
- `SEARCH-CONSOLE.md` — 公開後のSearch Console登録・インデックス申請手順

## SEO
- 3ページそれぞれに固有のtitle・description・canonical URL・OGPを設定
- HomeとBiographyに、北地雄を主対象とする`ProfilePage` / `Person`構造化データを設定
- Publicationsに`CollectionPage` / `Person`構造化データを設定
- Search Consoleに提出するサイトマップ: `https://yourehalab.github.io/sitemap.xml`

## GitHub
公開サイトでは GitHub profile `https://github.com/yourehalab` にリンクしています。提供された `yourehalab/homecare-rehab-evaluation` はprivate repositoryのため、公開サイトからprivate repoへは直接リンクしていません。

## Preview
`index.html` をブラウザで開くだけで確認できます。

Last updated: 2026-08-13
