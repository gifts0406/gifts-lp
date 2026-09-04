# gifts-lp

株式会社gifts が公開するランディングページと、掲載に必要な表記の配信先。
**GitHub Pages で公開している。**

## このリポジトリの決まり

- **公開してよいものしか置かない。**公開リポジトリなので、下書き・未公開の企画・顧客情報は入れない
- 中身は `lp-factory/build_site.py` が生成する。**ここを直接編集しない**
- 更新は `lp-factory/deploy.sh` を実行する

## 構成

```
/                入口（noindex）
/privacy/        プライバシーポリシー
/tokushoho/      特定商取引法に基づく表記
/<案件名>/       各LP
```

法定ページの本文は Vault の `_wix_to_wordpress/content/` が正本。
