# ワークショップ プロジェクト

## はじめに
このプロジェクトには、AIエージェントチームが事前設定されています。
あなたのサービスアイデアをClaude Codeに伝えるだけで、チームが自動的にWebサイトを構築します。

## エージェントチーム

| Agent | 役割 | 何をしてくれるか |
|-------|------|-----------------|
| Sherpa | 計画役 | アイデアを具体的なタスクに分解 |
| Artisan | 実装役 | Next.js + Tailwind CSSでコードを実装 |
| Radar | 検証役 | ビルド確認・品質チェック |

## 技術制約

- Next.js Static Export（`output: 'export'`）
- Tailwind CSS
- DB無し、API無し、フロントエンドのみ
- 日本語UI
- レスポンシブデザイン
- `npm run build` でエラーが出ないこと

## ワークフロー

参加者がサービスアイデアを伝えたら:
1. Sherpa でタスク分解を行う
2. Artisan で実装する
3. Radar でビルド確認・品質検証する
4. 結果を参加者に報告する

## 出力言語
全ての出力は日本語。

## Agent Team Framework

This project uses [Agent Orchestrator](https://github.com/luna-matching/agent-orchestrator).
Agent definitions are in `.claude/agents/`. Framework protocol is in `.claude/agents/_framework.md`.

### Key Rules
- Hub-spoke pattern: all communication through orchestrator (Nexus/Rally)
- CEO handles business decisions before technical execution
- File ownership is law in parallel execution
- Guardrails L1-L4 for safe autonomous execution
- All outputs in Japanese
- Conventional Commits, no agent names in commits/PRs

### Business Context
- `.agents/LUNA_CONTEXT.md` - Business context for CEO decisions
- `.agents/PROJECT.md` - Shared knowledge across agents

## Agent Team Framework

This project uses [Hino Orchestrator](https://github.com/hinominant/hino-orchestrator).
Agent definitions are in `.claude/agents/`. Framework protocol is in `.claude/agents/_framework.md`.

### Key Rules
- Hub-spoke pattern: all communication through orchestrator (Nexus/Rally)
- CEO handles business decisions before technical execution
- File ownership is law in parallel execution
- Guardrails L1-L4 for safe autonomous execution
- All outputs in Japanese
- Conventional Commits, no agent names in commits/PRs

### Business Context
- `.agents/LUNA_CONTEXT.md` - Business context for CEO decisions
- `.agents/PROJECT.md` - Shared knowledge across agents
