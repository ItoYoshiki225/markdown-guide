# Markdown 書き方ガイド & テンプレート集

初心者から上級者まで使える、Markdown の学習ガイドとテンプレート集です。
GitHub 上でそのまま表示を確認しながら学べるように作っています。

## 📚 目次

| レベル | ドキュメント | 内容 |
| :--- | :--- | :--- |
| 🌱 初級 | [01-beginner.md](docs/01-beginner.md) | 見出し・段落・強調・リスト・リンク・画像 |
| 🌿 中級 | [02-intermediate.md](docs/02-intermediate.md) | 表・コードブロック・引用・タスクリスト・脚注 |
| 🌳 上級 | [03-advanced.md](docs/03-advanced.md) | GitHub 独自記法・Mermaid・数式・HTML・アラート |
| ⚡ 早見表 | [cheatsheet.md](docs/cheatsheet.md) | よく使う記法の一覧 |
| ✅ 規約 | [style-guide.md](docs/style-guide.md) | 読みやすい Markdown を書くためのルール |

## 📝 テンプレート

[templates/](templates/) フォルダに、すぐにコピーして使えるテンプレートがあります。

| テンプレート | 用途 |
| :--- | :--- |
| [README_template.md](templates/README_template.md) | リポジトリの README |
| [design-doc_template.md](templates/design-doc_template.md) | 設計書・仕様書 |
| [meeting-notes_template.md](templates/meeting-notes_template.md) | 議事録 |
| [daily-report_template.md](templates/daily-report_template.md) | 日報・週報 |
| [test-report_template.md](templates/test-report_template.md) | テスト結果報告書 |
| [blog-article_template.md](templates/blog-article_template.md) | 技術ブログ記事（Qiita / Zenn など） |

## 📁 フォルダ構成

```text
markdown-guide/
├── README.md                    # このファイル
├── LICENSE
├── .gitignore
├── .editorconfig                # エディタ共通設定
├── .markdownlint.json           # Markdown の文法チェック設定
├── .vscode/
│   └── extensions.json          # おすすめ拡張機能
├── .github/
│   ├── ISSUE_TEMPLATE/          # Issue 作成時のテンプレート
│   ├── pull_request_template.md # PR 作成時のテンプレート
│   └── workflows/
│       └── markdownlint.yml     # push 時に自動で文法チェック
├── docs/                        # 学習ガイド本体
├── templates/                   # コピーして使うテンプレート
└── assets/
    └── images/                  # 画像置き場
```

## 🚀 使い方

1. まずは [初級編](docs/01-beginner.md) から順番に読む
2. 気になる記法は [早見表](docs/cheatsheet.md) で確認する
3. 実際に書くときは [templates/](templates/) からコピーして使う

### ローカルでプレビューする

- **VS Code**：`Ctrl + Shift + V`（Mac は `Cmd + Shift + V`）でプレビュー表示
- **おすすめ拡張機能**
  - [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)：文法チェック
  - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)：目次生成・ショートカット
  - [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)：図のプレビュー

### 文法チェックを手元で実行する

```bash
npx markdownlint-cli2 "**/*.md"
```

## 📄 ライセンス

[MIT License](LICENSE)
