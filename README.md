## 概要

ポートレートサイト

## 使用技術

| 言語、フレームワーク | バージョン | サイト URL                                 |
| -------------------- | ---------- | ------------------------------------------ |
| node                 | 24.1.0     | https://nodejs.org/ja/blog/release/v24.1.0 |
| biome                | 1.9.4     | https://biomejs.dev/ja/                    |
| normalize.css | ^8.0.1 4     | https://biomejs.dev/ja/    |
| next | 15.3.3     | https://biomejs.dev/ja/    |

## ディレクトリ構成

<pre>
/ PORTRAIT-LP
├─ app
│ ├─ feature
│ │ ├─ (Home)
│ │ │ └─ Home
│ │ │ ├─ components
│ │ │ │ └─ content.tsx
│ │ │ ├─ Home.tsx
│ │ │ └─ Home.stories.tsx
│ │ ├─ (About)
│ │ │ └─ About
│ │ │ ├─ components
│ │ │ │ └─ content.tsx
│ │ │ ├─ About.tsx
│ │ │ └─ About.stories.tsx
│ │ ├─ (Work)
│ │ │ └─ Work
│ │ │ ├─ components
│ │ │ │ └─ content.tsx
│ │ │ ├─ Work.tsx
│ │ │ └─ Work.stories.tsx
│ │ ├─ (Portrait)
│ │ │ └─ Portrait
│ │ │ ├─ components
│ │ │ │ └─ content.tsx
│ │ │ ├─ Portrait.tsx
│ │ │ └─ Portrait.stories.tsx
│ │ ├─ (Snap)
│ │ │ └─ Snap
│ │ │ ├─ components
│ │ │ │ └─ content.tsx
│ │ │ ├─ Snap.tsx
│ │ │ └─ Snap.stories.tsx
│ │ └─ (Contact)
│ │ └─ Contact
│ │ ├─ components
│ │ │ └─ content.tsx
│ │ ├─ Contact.tsx
│ │ └─ Contact.stories.tsx
│ ├─ components
│ │ └─ common
│ │ ├─ Title.tsx
│ │ ├─ SubTitle.tsx
│ │ ├─ Menu.tsx
│ │ └─ SpMenu.tsx
│ ├─ (Home)
│ │ └─ home
│ │ └─ page.tsx
│ ├─ (About)
│ │ └─ about
│ │ └─ page.tsx
│ ├─ (Work)
│ │ └─ work
│ │ ├─ [slug]
│ │ │ └─ page.tsx
│ │ └─ page.tsx
│ ├─ (Portrait)
│ │ └─ portrait
│ │ └─ page.tsx
│ ├─ (Snap)
│ │ └─ snap
│ │ └─ snap.tsx
│ ├─ (Contact)
│ │ └─ contact
│ │ └─ contact.tsx
│ ├─ hooks
│ │ └─ useBooleanState.tsx
│ ├─ provider
│ │ └─ AppThemeProvider.tsx
│ ├─ types
│ ├─ global.css
│ ├─ layout.tsx
│ └─ page.tsx
├─ gitignore
├─ biome
├─ next-env.d.ts
├─ next.config.ts
├─ package-lock.json
├─ package.json
├─ README.md
└─ tsconfig.json
</pre>

## コミットルール
| 絵文字 | 意味                       | 説明                                           |
|--------|----------------------------|------------------------------------------------|
| 🎉     | 初回コミット               | 最初のコミット。プロジェクト開始の合図         |
| 🔥     | ファイル削除               | 不要なコードやファイルを削除                   |
| 🐛     | バグ修正                   | バグや不具合の修正                             |
| ✨     | 新機能追加                 | 新しい機能や要素の実装                         |
| 📝     | ドキュメント追加・修正     | READMEやコメントなどドキュメント関連の更新     |
| ✅     | テスト追加・修正           | ユニットテストやE2Eテストなどの追加・変更     |
| 🔒     | セキュリティ修正           | セキュリティ、プライバシーに関する修正         |
| 🚨     | 警告修正                   | コンパイラやリンターの警告対応                 |
| 🚧     | 作業途中（WIP）            | 未完成の作業。まだマージしない方がいい         |
| ➕     | 依存追加                   | ライブラリやパッケージの追加                   |
| ♻️     | リファクタリング           | 動作は変えずにコード構造を改善                 |
| 🔀     | マージコミット             | ブランチの統合                                 |
| 🔨     | 改修                       | 改良・修正作業全般。小さな改善も含む           |



## その他
### biomeの設定について
https://github.com/yoshikouki/honon/blob/main/biome.json