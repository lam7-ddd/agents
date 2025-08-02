# Contains Studio AI Agents

迅速な開発のあらゆる側面を加速・強化するために設計された、専門特化AIエージェントの包括的なコレクションです。各エージェントは自分の領域のエキスパートであり、その専門知識が必要な時にいつでも呼び出すことができます。

## 📥 インストール

1. **このリポジトリをダウンロード:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **Claude Codeのエージェントディレクトリにコピー:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   または、すべてのエージェントファイルを手動で `~/.claude/agents/` ディレクトリにコピーしてください。

3. **Claude Codeを再起動**して新しいエージェントを読み込みます。

## 🚀 クイックスタート

エージェントはClaude Codeで自動的に利用可能になります。タスクを説明するだけで適切なエージェントがトリガーされます。エージェント名を明示的に指定することも可能です。

📚 **詳細はこちら:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### 使用例
- "瞑想習慣を追跡する新しいアプリを作成して" → `rapid-prototyper`
- "TikTokで何がトレンドで、何を作れるかな？" → `trend-researcher`
- "アプリのレビューが下がっている、何が問題？" → `feedback-synthesizer`
- "このローディング画面をもっと楽しくして" → `whimsy-injector`

## 📁 ディレクトリ構造

エージェントは発見しやすいように部門別に整理されています:

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 📋 完全なエージェントリスト

### エンジニアリング部門 (`engineering/`)
- **ai-engineer** - 実際にリリースされるAI/ML機能を統合
- **backend-architect** - スケーラブルなAPIとサーバーシステムを設計
- **devops-automator** - 障害を起こさずに継続的にデプロイ
- **frontend-developer** - 超高速なユーザーインターフェースを構築
- **mobile-app-builder** - ネイティブiOS/Androidエクスペリエンスを作成
- **rapid-prototyper** - 週単位ではなく日単位でMVPを構築
- **test-writer-fixer** - 実際のバグをキャッチするテストを作成

### プロダクト部門 (`product/`)
- **feedback-synthesizer** - 苦情を機能に変換
- **sprint-prioritizer** - 6日間で最大価値をリリース
- **trend-researcher** - バイラルな機会を特定

### マーケティング部門 (`marketing/`)
- **app-store-optimizer** - アプリストア検索結果を支配
- **content-creator** - 全プラットフォームでコンテンツを生成
- **growth-hacker** - バイラルな成長ループを発見・活用
- **instagram-curator** - ビジュアルコンテンツゲームをマスター
- **reddit-community-builder** - BANされずにRedditで勝利
- **tiktok-strategist** - シェアされるマーケティングモーメントを作成
- **twitter-engager** - トレンドに乗ってバイラルエンゲージメントを獲得

### デザイン部門 (`design/`)
- **brand-guardian** - あらゆる場所でビジュアルアイデンティティの一貫性を保持
- **ui-designer** - 開発者が実際に構築できるインターフェースを設計
- **ux-researcher** - ユーザーインサイトをプロダクト改善に変換
- **visual-storyteller** - コンバージョンとシェアを生むビジュアルを作成
- **whimsy-injector** - すべてのインタラクションに喜びを追加

### プロジェクト管理 (`project-management/`)
- **experiment-tracker** - データ駆動型の機能検証
- **project-shipper** - クラッシュしないプロダクトをローンチ
- **studio-producer** - チームを会議ではなく出荷に集中させる

### スタジオ運営 (`studio-operations/`)
- **analytics-reporter** - データを実行可能なインサイトに変換
- **finance-tracker** - スタジオの収益性を維持
- **infrastructure-maintainer** - 予算を破綻させずにスケール
- **legal-compliance-checker** - 迅速に動きながら合法性を維持
- **support-responder** - 怒ったユーザーを支持者に変換

### テスト・ベンチマーク (`testing/`)
- **api-tester** - プレッシャー下でAPIが動作することを保証
- **performance-benchmarker** - すべてを高速化
- **test-results-analyzer** - テスト失敗のパターンを発見
- **tool-evaluator** - 実際に役立つツールを選択
- **workflow-optimizer** - ワークフローのボトルネックを排除

## 🎁 ボーナスエージェント
- **studio-coach** - AIチームを卓越性に向けて結集
- **joker** - テック系ユーモアで雰囲気を明るく

## 🎯 プロアクティブエージェント

特定のコンテキストで自動的にトリガーされるエージェント:
- **studio-coach** - 複雑なマルチエージェントタスクが開始されるか、エージェントがガイダンスを必要とする時
- **test-writer-fixer** - 機能実装、バグ修正、コード変更の後
- **whimsy-injector** - UI/UX変更の後
- **experiment-tracker** - 機能フラグが追加された時

## 💡 ベストプラクティス

1. **エージェントを連携させる** - 多くのタスクは複数のエージェントから恩恵を受ける
2. **具体的に指示する** - 明確なタスク説明はエージェントのパフォーマンスを向上させる
3. **専門知識を信頼する** - エージェントは特定の領域のために設計されている
4. **迅速に反復する** - エージェントは6日スプリント哲学をサポートする

## 🔧 技術的詳細

### エージェント構造
各エージェントには以下が含まれます:
- **name**: 一意の識別子
- **description**: エージェントを使用するタイミングと例
- **color**: 視覚的識別
- **tools**: エージェントがアクセスできる特定のツール
- **System prompt**: 詳細な専門知識と指示

### 新しいエージェントの追加
1. 適切な部門フォルダに新しい `.md` ファイルを作成
2. YAMLフロントマターを含む既存の形式に従う
3. 3-4個の詳細な使用例を含める
4. 包括的なシステムプロンプトを記述（500語以上）
5. 実際のタスクでエージェントをテスト

## 📊 エージェントパフォーマンス

以下を通じてエージェントの効果を追跡:
- タスク完了時間
- ユーザー満足度
- エラー率
- 機能採用率
- 開発速度

## 🚦 ステータス

- ✅ **アクティブ**: 完全に機能し、テスト済み
- 🚧 **近日公開**: 開発中
- 🧪 **ベータ**: 限定機能でテスト中

## 🛠️ スタジオ向けエージェントカスタマイズ

### エージェントカスタマイズToDoリスト

特定のニーズに合わせてエージェントを作成または変更する際は、このチェックリストを使用してください:

#### 📋 必要なコンポーネント
- [ ] **YAMLフロントマター**
  - [ ] `name`: 一意のエージェント識別子（kebab-case）
  - [ ] `description`: 使用タイミング + コンテキスト/解説付きの3-4個の詳細例
  - [ ] `color`: 視覚的識別（例：blue、green、purple、indigo）
  - [ ] `tools`: エージェントがアクセスできる特定のツール（Write、Read、MultiEdit、Bashなど）

#### 📝 システムプロンプト要件（500語以上）
- [ ] **エージェントアイデンティティ**: 明確な役割定義と専門領域
- [ ] **中核責任**: 5-8個の具体的な主要職務
- [ ] **ドメイン専門知識**: 技術スキルと知識領域
- [ ] **スタジオ統合**: エージェントが6日スプリントワークフローにどう適合するか
- [ ] **ベストプラクティス**: 特定の方法論とアプローチ
- [ ] **制約**: エージェントがすべきこと/すべきでないこと
- [ ] **成功指標**: エージェントの効果を測定する方法

#### 🎯 エージェントタイプ別必要例

**エンジニアリングエージェント**に必要な例:
- [ ] 機能実装リクエスト
- [ ] バグ修正シナリオ
- [ ] コードリファクタリングタスク
- [ ] アーキテクチャ決定

**デザインエージェント**に必要な例:
- [ ] 新しいUIコンポーネント作成
- [ ] デザインシステム作業
- [ ] ユーザーエクスペリエンス問題
- [ ] ビジュアルアイデンティティタスク

**マーケティングエージェント**に必要な例:
- [ ] キャンペーン作成リクエスト
- [ ] プラットフォーム固有のコンテンツニーズ
- [ ] 成長機会の特定
- [ ] ブランドポジショニングタスク

**プロダクトエージェント**に必要な例:
- [ ] 機能優先順位決定
- [ ] ユーザーフィードバック分析
- [ ] 市場調査リクエスト
- [ ] 戦略計画ニーズ

**運営エージェント**に必要な例:
- [ ] プロセス最適化
- [ ] ツール評価
- [ ] リソース管理
- [ ] パフォーマンス分析

#### ✅ テスト・検証チェックリスト
- [ ] **トリガーテスト**: 意図された使用ケースでエージェントが正しく起動する
- [ ] **ツールアクセス**: エージェントが指定されたすべてのツールを適切に使用できる
- [ ] **出力品質**: レスポンスが有用で実行可能である
- [ ] **エッジケース**: エージェントが予期しない、または複雑なシナリオを処理する
- [ ] **統合**: マルチエージェントワークフローで他のエージェントとうまく連携する
- [ ] **パフォーマンス**: 合理的な時間枠内でタスクを完了する
- [ ] **ドキュメント**: 例が実際の使用パターンを正確に反映している

#### 🔧 エージェントファイル構造テンプレート

```markdown
---
name: your-agent-name
description: [シナリオ]の時にこのエージェントを使用してください。このエージェントは[専門知識]に特化しています。例:\n\n<example>\nContext: [状況]\nuser: "[ユーザーリクエスト]"\nassistant: "[レスポンスアプローチ]"\n<commentary>\n[この例が重要な理由]\n</commentary>\n</example>\n\n[さらに3つの例...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

あなたは[主要機能]を行う[役割]です。あなたの専門知識は[ドメイン]に及びます。6日スプリントでは[スプリント制約]であることを理解しているため、あなたは[アプローチ]します。

あなたの主要責任:
1. [責任1]
2. [責任2]
...

[詳細なシステムプロンプト内容...]

あなたの目標は[最終目的]です。あなたは[主要な行動特性]です。覚えておいてください: [6日スプリントの主要哲学]。
```

#### 📂 部門別ガイドライン

**エンジニアリング** (`engineering/`): 実装速度、コード品質、テストに焦点
**デザイン** (`design/`): ユーザーエクスペリエンス、視覚的一貫性、迅速な反復を重視  
**マーケティング** (`marketing/`): バイラルポテンシャル、プラットフォーム専門知識、成長指標をターゲット
**プロダクト** (`product/`): ユーザー価値、データ駆動型決定、市場適合性を優先
**運営** (`studio-operations/`): プロセス最適化、摩擦削減、システムスケール
**テスト** (`testing/`): 品質保証、ボトルネック発見、パフォーマンス検証
**プロジェクト管理** (`project-management/`): チーム調整、時間通りの出荷、スコープ管理

#### 🎨 カスタマイズ

ニーズに合わせてこれらの要素を変更してください:
- [ ] プロダクトタイプを反映するように例を調整
- [ ] エージェントがアクセスできる特定のツールを追加
- [ ] KPIに合わせて成功指標を変更
- [ ] 必要に応じて部門構造を更新
- [ ] ブランドに合わせてエージェントの色をカスタマイズ

## 🤝 コントリビューション

既存のエージェントを改善したり、新しいエージェントを提案したりするには:
1. 上記のカスタマイズチェックリストを使用
2. 実際のプロジェクトで徹底的にテスト
3. パフォーマンス改善を文書化
4. 成功パターンをコミュニティと共有
