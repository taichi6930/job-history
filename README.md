# job-history

職務経歴書

## セットアップ

```bash
npm install
```

## マークダウンのlint

### ローカルで実行

```bash
# すべてのlintを実行
npm run lint

# markdownlintのみ
npm run lint:md

# textlintのみ
npm run lint:text

# 自動修正
npm run lint:fix
```

### CI/CD

GitHub Actionsで自動的にマークダウンのlintが実行されます。

- mainブランチへのpush時
- feature/**ブランチへのpush時
- mainブランチへのプルリクエスト時

## 設定ファイル

- `config/.textlintrc` - textlintの設定
- `config/.markdownlint.jsonc` - markdownlintの設定
