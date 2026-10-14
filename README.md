# Mystudy

資格・試験勉強と、複数テーマの学習ノートをまとめて管理するリポジトリです。

## ディレクトリ構成

```
Mystudy/
├── README.md          # このファイル
├── PLAN.md            # 6か月の学習計画・週の時間割
├── PROGRESS.md        # 目標一覧・進捗チェックリスト
├── templates/         # ノートのひな形
│   ├── note.md        #   学習ノート用
│   └── exam.md        #   資格・試験の計画用
└── topics/            # テーマ別の学習内容
    └── <テーマ名>/
        ├── README.md  #   テーマの概要・目標（資格なら exam.md を元に作成）
        ├── notes/     #   学習ノート
        └── exercises/ #   問題演習・間違えた問題の記録
```

## 使い方

1. 新しいテーマを始めるときは `topics/<テーマ名>/` を作る（例: `topics/fe-exam/`、`topics/english/`）
2. 資格・試験なら `templates/exam.md` を、それ以外なら簡単な概要を `topics/<テーマ名>/README.md` に書く
3. 学習したら `templates/note.md` をコピーして `notes/` に保存する
   - ファイル名の例: `notes/2026-10-14_ネットワーク基礎.md`
4. 週に1回ほど `PROGRESS.md` を更新して進み具合を振り返る

## 命名ルール

- テーマのディレクトリ名は英小文字とハイフン（例: `aws-saa`, `fe-exam`）
- ノートは `YYYY-MM-DD_タイトル.md`
