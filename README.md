# MF-Claude-Kit

マネーフォワード クラウド会計・クラウド勤怠を Claude から扱うための設定一式です。
Claude Desktop の `Code` タブでこのフォルダを開くと、会計の MCP サーバーに
つながった状態で作業できます。

## ダウンロード

[Releases](../../releases/latest) の `mf-claude-kit.zip` を取得します。

## 入れ方

1. zip を展開すると `MF-Claude-Kit` フォルダができます
2. フォルダごと `ドキュメント` の下に置きます
3. 中の `はじめにお読みください.html` をブラウザで開きます

あとの手順はその HTML に書いてあります。

## 中身

| 名前 | 中身 |
|------|------|
| `はじめにお読みください.html` | 導入手順。管理者がすることと、使う人がすること |
| `CLAUDE.md` | Claude の運用ルール。承認なしに登録しない、削除は画面で行う、など |
| `.mcp.json` | 接続先の設定（会計の MCP サーバーとブラウザ操作） |
| `勘定科目ルール.md` | 摘要のキーワードと勘定科目の対応表 |
| `勤怠/` | 改善基準告示・変形労働時間制・取り込み様式・自社の設定 |
| `.claude/skills/` | 未仕訳確認・月次レビュー・勤怠取り込みなどの手順 |

## 使う前に必要なもの

| 名前 | 入手先 |
|------|--------|
| Claude Desktop | https://claude.com/download |
| Git | https://git-scm.com/downloads |
| Google Chrome | 勤怠を使うときだけ要ります。Claude in Chrome 拡張 https://chromewebstore.google.com/detail/claude/fcoeoabgfenejglbffodgkkbkcdhcgfn を入れ、Claude デスクトップアプリの `Settings` ＞ `Connectors` ＞ `Claude in Chrome` ＞ `Configure` でトグルをオンにします |

マネーフォワード側は、クラウド会計の「全権管理」権限のあるアカウントで
アプリ連携の設定を行います。

## 注意

- `勤怠/うちの設定.md` は空欄のまま配布しています。自社の値は各自で書き込みます
- 顧問先名・金額・従業員の氏名は、このリポジトリに置きません

## 作成

SX
