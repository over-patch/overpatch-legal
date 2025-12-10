# overpatch-legal

このリポジトリは、OverPatchが提供するアプリケーションの利用規約（Terms of Service）およびプライバシーポリシー（Privacy Policy）を公開するためのGitHub Pages用リポジトリです。

## ディレクトリ構成

各アプリケーションごとにディレクトリが分かれており、その中に利用規約とプライバシーポリシーのHTMLファイルが配置されています。また、それぞれのドキュメントには日本語（`ja`）と英語（`en`）の版が用意されています。

```
.
├── README.md
├── index.html                # 全ページへのリンク一覧
├── hanahana/                 # アプリ: hanahana
│   ├── terms_ja.html         # 利用規約 (日本語)
│   ├── terms_en.html         # Terms of Service (English)
│   ├── privacy_ja.html       # プライバシーポリシー (日本語)
│   └── privacy_en.html       # Privacy Policy (English)
├── juggler/                  # アプリ: juggler
│   ├── ...
└── slitherlink/              # アプリ: slitherlink
    └── ...
```

## 使い方

### 新しいアプリを追加する場合

1. アプリ名のディレクトリをルートに作成します。（例: `new-app`）
2. そのディレクトリの中に以下の4つのHTMLファイルを作成します。
    - `terms_ja.html`
    - `terms_en.html`
    - `privacy_ja.html`
    - `privacy_en.html`
3. それぞれのファイルに適切な内容を記述してください。

### ページのURL

GitHub Pagesとして公開された場合、各ページのURLは以下の形式になります。

- `https://over-patch.github.io/overpatch-legal/[アプリ名]/terms_ja.html`
- `https://over-patch.github.io/overpatch-legal/[アプリ名]/privacy_en.html`
など

## リンク一覧

### index
- [一覧ページ](https://over-patch.github.io/overpatch-legal/index.html)

### Hanahana
- [利用規約 (日本語)](https://over-patch.github.io/overpatch-legal/hanahana/terms_ja.html)
- [Terms of Service (English)](https://over-patch.github.io/overpatch-legal/hanahana/terms_en.html)
- [プライバシーポリシー (日本語)](https://over-patch.github.io/overpatch-legal/hanahana/privacy_ja.html)
- [Privacy Policy (English)](https://over-patch.github.io/overpatch-legal/hanahana/privacy_en.html)

### Juggler
- [利用規約 (日本語)](https://over-patch.github.io/overpatch-legal/juggler/terms_ja.html)
- [Terms of Service (English)](https://over-patch.github.io/overpatch-legal/juggler/terms_en.html)
- [プライバシーポリシー (日本語)](https://over-patch.github.io/overpatch-legal/juggler/privacy_ja.html)
- [Privacy Policy (English)](https://over-patch.github.io/overpatch-legal/juggler/privacy_en.html)

### Slitherlink
- [利用規約 (日本語)](https://over-patch.github.io/overpatch-legal/slitherlink/terms_ja.html)
- [Terms of Service (English)](https://over-patch.github.io/overpatch-legal/slitherlink/terms_en.html)
- [プライバシーポリシー (日本語)](https://over-patch.github.io/overpatch-legal/slitherlink/privacy_ja.html)
- [Privacy Policy (English)](https://over-patch.github.io/overpatch-legal/slitherlink/privacy_en.html)
