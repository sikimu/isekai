# 設定ファイル管理について

このディレクトリには物語の基本設定が含まれています。

## ファイル構成
- `world.md` - 世界観設定（魔法体系、社会システムなど）
- `characters.md` - キャラクター設定
- `summary.md` - あらすじ・展開
- `summaries/` - 各章ごとの詳細なサマリー
  - `prologue.md` - プロローグのサマリー
  - `chapter1.md` - 第1章のサマリー
  - `chapter2.md` - 第2章のサマリー
  - 以降、各章のサマリー

## 更新ガイドライン
1. 各設定ファイルは、物語の進行に応じて随時更新してください
2. 新しい設定要素が登場した場合は、適切なファイルに追記してください
3. 矛盾が発生しないよう、更新時は既存の設定を確認してください

## 設定追加時の注意点
- 魔法関連の新要素 → `world.md`
- 新キャラクター登場 → `characters.md`
- ストーリー展開の更新 → `summary.md`
- 各章の詳細な展開 → `summaries/chapter*.md`

## フォルダ構造
```
settings/
├── README.md          # 本ファイル
├── world.md          # 世界観設定
├── characters.md     # キャラクター設定
├── summary.md        # あらすじ・展開
└── summaries/        # 各章のサマリー
    ├── README.md     # サマリーフォルダの説明
    ├── prologue.md   # プロローグ
    ├── chapter1.md   # 第1章
    ├── chapter2.md   # 第2章
    └── ...          # 以降の章