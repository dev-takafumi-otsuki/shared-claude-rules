# Shared Claude Rules

複数プロジェクト間で共有するClaude Code設定ファイル。

## 使い方

各プロジェクトのCLAUDE.mdで以下のようにインポート:

```markdown
@~/shared-claude-rules/sdlc-process.md
@~/shared-claude-rules/ai-behavior.md
@~/shared-claude-rules/feedback-loop.md
```

## ファイル一覧

| ファイル | 内容 |
|---------|------|
| `sdlc-process.md` | 開発プロセスと承認ゲート（大規模/小規模改修の判定基準） |
| `ai-behavior.md` | AIの振る舞い（言語設定、自律性制限） |
| `feedback-loop.md` | フィードバックループと手戻り対応 |
