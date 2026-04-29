# 管工事PASS - ディレクトリ構成

GitHub Pages URL: https://flownode-dev.github.io/kankoiji-pass/

```
kankoiji-pass/                    ← リポジトリルート
│
├── index.html                    ← トップページ
├── sitemap.xml                   ← サイトマップ（Search Console登録用）
├── robots.txt                    ← クローラー制御
│
├── css/
│   ├── style.css                 ← 共通スタイル（全ページで読み込む）
│   └── _partials.html            ← ヘッダー・フッターのスニペット集（参照用）
│
├── assets/
│   ├── favicon.ico               ← ファビコン（後で作成）
│   ├── ogp.png                   ← OGP画像 1200×630px（後で作成）
│   └── img/                      ← 画像ファイル置き場
│
├── kakomon/                      ← 過去問演習
│   ├── index.html                ← 過去問トップ（年度・分野別一覧）
│   ├── r06/
│   │   └── index.html            ← 令和6年度
│   ├── r05/
│   │   └── index.html            ← 令和5年度
│   ├── r04/
│   │   └── index.html
│   ├── r03/
│   │   └── index.html
│   ├── r02/
│   │   └── index.html
│   └── bunya/                    ← 分野別出題
│       ├── kucho/index.html      ← 空調設備
│       ├── kyuhaisu/index.html   ← 給排水
│       └── ...
│
├── data/                         ← 過去問JSONデータ
│   ├── r06.json                  ← 令和6年度問題データ
│   ├── r05.json
│   ├── r04.json
│   └── ...
│
├── bunya/                        ← 分野別解説
│   ├── index.html                ← 分野一覧
│   ├── kiso/index.html           ← 一般基礎（流体・熱・電気）
│   ├── kucho/index.html          ← 空調設備
│   ├── kyuhaisu/index.html       ← 給排水・衛生設備
│   ├── shobo/index.html          ← 消防設備
│   ├── kotei/index.html          ← 工程管理
│   ├── hinshitsu/index.html      ← 品質・安全管理
│   └── hoki/index.html           ← 法規
│
├── niji/                         ← 第二次検定対策
│   └── index.html
│
├── yougo/                        ← 用語集
│   └── index.html
│
├── roadmap/                      ← 合格ロードマップ
│   └── index.html
│
├── column/                       ← コラム記事
│   ├── index.html                ← コラム一覧
│   ├── what-is/index.html        ← 1級管工事とは？
│   ├── study-method/index.html   ← 勉強方法
│   ├── experience-writing/index.html ← 経験記述の書き方
│   ├── salary/index.html         ← 年収・キャリア
│   └── r06-trend/index.html      ← 令和6年度傾向
│
├── privacy/
│   └── index.html                ← プライバシーポリシー ✅完成
│
├── disclaimer/
│   └── index.html                ← 免責事項 ✅完成
│
└── contact/
    └── index.html                ← お問い合わせ（Googleフォーム埋め込み）
```

## ファイル作成状況

| ファイル | 状態 |
|---------|------|
| css/style.css | ✅ 完成 |
| css/_partials.html | ✅ 完成（スニペット集） |
| sitemap.xml | ✅ 完成 |
| robots.txt | ✅ 完成 |
| privacy/index.html | ✅ 完成 |
| disclaimer/index.html | ✅ 完成 |
| index.html（トップ） | 🔲 未作成 |
| contact/index.html | 🔲 未作成 |
| kakomon/index.html | 🔲 未作成 |
| bunya/index.html | 🔲 未作成 |
| niji/index.html | 🔲 未作成 |
| column/* | 🔲 未作成 |

## GitHubへのアップロード方法

1. GitHubのリポジトリページを開く
2. 「Add file」→「Upload files」
3. ファイルをドラッグ＆ドロップ
4. 「Commit changes」をクリック

※フォルダごとアップする場合は、フォルダをそのままドラッグしてOK
