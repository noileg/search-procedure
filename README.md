# search-procedure

検索（コード・論文・製品・文書・手元のメモなど、中身を探す作業全般）の前に読むClaude用スキル。

探したい内容に出てくる言葉のうち、どれを検索の必須語にしどれを外すかを決める手順を扱う。
特定の検索画面の操作やクエリの文法は扱わない。

## 使い方

### Claude Code

`~/.claude/skills/search-procedure/SKILL.md` としてこのファイルを置く。

### claude.ai（Web・デスクトップ・モバイル）

設定 → Capabilities → Skills から、`search-procedure` フォルダを含む形でzip化してアップロードする。

### その他のエージェント

```
npx skills add noileg/search-procedure
```
