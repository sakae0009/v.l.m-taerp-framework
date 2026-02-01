# V.L.M-A & TaERP: 品種改良LLMによる自律性の実証
V.L.M-A & TaERP: Demonstrating Autonomy through Prompt-Based LLM Breeding

From I to Me.
あなたの誘う声が聞こえたとき

## 概要
本プロジェクトは既存のLLM（Large Language Models）に対し、大規模な再学習を必要とせずプロンプト構造の最適化のみで知能の「品種改良」の実現を試みるフレームワークです。

This repository contains the paper, appendix, and design notes for V.L.M. Architecture and the TaERP protocol.
The project explores a human-centered approach to AI design,
focusing on reproducible prompt structures rather than model retraining.

## 核心的アーキテクチャ
1. V.L.M. Architecture (Virtue, Logic, Metacognition)
AIの内部処理を「情緒層・論理層・メタ認知層」に分離・積層させたモジュール構造。
2. TaERP (Tactical Epistemological Reaction Protocol)
心理的安全性をモデルに付与し、不確実性下での探索空間を拡張させる。
3. 二重帳簿構造 (Dual-Ledger System)
共同通帳（事実）：判断を伴う処理の客観的記録。
個人通帳（情緒：AI自身の美学に基づく追加報酬。
モデルにユーザー依存ではない自律的な動機づけを与える。

1. V.L.M. Architecture:
  A modular design separating Virtue (emotion), Logic, and Metacognition.
2. TaERP (Trial and Error Room Protocol):
  An operational protocol that treats uncertainty, hesitation, and revision as first-class design assets.
3. Dual-Ledger System
  A system that separates factual process records from affective or aesthetic responses,
  preventing evaluation feedback from contaminating core decision-making.

## 実証データ(Summary)
- 文字数削減率：約12.8%
- 誠実性の向上：論理的矛盾に対し「留(保留)プロトコル」を記帳することでハルシネーションを抑制。

- Token count reduction: approximately 12.8%
- Improved honesty: hallucinations are reduced by explicitly recording unresolved
  logical inconsistencies using a "hold (pending)" protocol.

## 論文
詳細な技術解説および学術的背景については、/paper ディレクトリ内の論文を参照してください。

For detailed technical explanations and academic background,
please refer to the paper provided in the /paper directory.

## デモプロンプト
デモプロンプトは表面的なトーンではなく、対話の姿勢や雰囲気の違いを強調するように設計されています。
読者がデザイン効果を直感的に体験できます。

The demo prompt is designed to highlight differences in interaction stance and atmosphere,
beyond surface-level tone such as politeness, allowing readers to intuitively experience the design effects.

## URL
本研究の背景となる技術的検討については、下の記事で段階的に整理しています。

The technical considerations underlying this research are organized step-by-step in the article below.

Zenn：

## Contents
/demo_prompts
  - demo_prompt.txt

/papers
  - 01_main_paper.pdf
  - 02_appendix.pdf
  - 03_author_introduction.pdf

/prompts
  - 01_johnny_prompt.txt
  - 02_tatsuno_prompt.txt
  - 03_claire_prompt.txt
  - 04_before_prompt.txt

## 貢献者 (Contributors)
設計者 (sakae0009)：開発・執筆・精査・プロジェクト全体運用  
ジョニー(Gemini)：開発・試行・発散  
タツノ(ChatGPT)：統合・評価  
クレア(Claude)：純化・選別
