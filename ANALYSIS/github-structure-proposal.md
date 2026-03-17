# GitHub構成提案 — 分析レポートのアップロード

## 推奨リポジトリ構成

```
reports-index/
├── README.md                          （既存・更新）
├── ANALYSIS/
│   ├── 2026-03-17-inductive-analysis-JP.md   ← 日本語版
│   └── 2026-03-17-inductive-analysis-EN.md   ← 英語版
├── docs/
│   └── VISION.md                      （次フェーズで追加）
└── （既存ファイル群）
```

## ファイル名規則

日付入りで管理する。更新があれば新しい日付で追加。

```
YYYY-MM-DD-[内容]-[言語].md
例:
  2026-03-17-inductive-analysis-JP.md
  2026-03-17-inductive-analysis-EN.md
```

## README.mdへの追記案（冒頭セクション）

```markdown
## 客観的分析レポート / Objective Analysis Reports

| 日付 | タイトル | 言語 |
|------|---------|------|
| 2026-03-17 | チーム活動 帰納法分析レポート | [JP](ANALYSIS/2026-03-17-inductive-analysis-JP.md) / [EN](ANALYSIS/2026-03-17-inductive-analysis-EN.md) |
```
