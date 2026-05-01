# barrie-privacy

株式会社バリーが提供するアプリのプライバシーポリシーを GitHub Pages で公開するリポジトリ。

## 公開 URL

GitHub Pages 有効化後、以下の URL で公開されます (`<USER>` は GitHub アカウント名):

- 共通: `https://<USER>.github.io/barrie-privacy/`
- GOGO!ソリティア: `https://<USER>.github.io/barrie-privacy/gogosolitaire/`

## 構成

```
.
├── index.html              # 各アプリへのリンク一覧
├── gogosolitaire/
│   └── index.html          # GOGO!ソリティア プライバシーポリシー
└── README.md
```

## デプロイ手順

1. GitHub で新規リポジトリ `barrie-privacy` を作成 (Public)
2. このフォルダを push
3. リポジトリの **Settings > Pages** で:
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
4. 数分待つと Pages が有効化されて URL が払い出される

## 更新

`gogosolitaire/index.html` を編集して push すれば、数分で反映されます。
