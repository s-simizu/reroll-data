# reroll-data

REROLL の種データ配信リポジトリ。**`https://data.rerolldeck.com/seed.json`** で配信される。

- `seed.json` は夜間バッチ（`.github/workflows/nightly-seed.yml`）が毎日自動 push する。
  **手で編集しないこと。**
- サイト側（プライバシーポリシー・デモページ）は別リポジトリ `reroll-site`
  （`https://rerolldeck.com`）。自動 push と手動更新を混ぜないために分けている。
- アプリ側の参照は `ios/REROLL/SeedStore.swift` の `RerollSite.base`。
