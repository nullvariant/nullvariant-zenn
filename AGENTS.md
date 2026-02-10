# nullvariant-zenn

## Overview

Zenn.dev向けの技術記事・本の管理リポジトリ。Zenn CLIのMarkdownフォーマットに準拠したコンテンツリポジトリ（コードなし）。

## Key Constraints

1. **Zenn記事フォーマット遵守**: 記事は `articles/*.md`、本は `books/*/` に配置。
2. **フロントマター必須**: `title`, `emoji`, `type`, `topics`, `published` を必ず含める。
3. **slug命名規則**: ファイル名がURLスラッグになる。英数字・ハイフンのみ、12〜50文字。

## Development

```bash
npx zenn preview    # ローカルプレビュー
```
