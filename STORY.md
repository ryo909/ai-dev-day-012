# Day012 Story — Weighted Option Calculator

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day012専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: weighted_scoring
- Mechanic: weighted_formula
- Input/Output: slider_weights_and_rows -> ranked_scores
- Audience Promise: transparent_tradeoff
- Publish Hook: 重みを動かすと順位差分が見える
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Add 2 safe enhancement components from selected_components while keeping the app single-page and stable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day012｜Weighted Option Calculator
重み付き評価で候補案の順位変化を比較できる計算ツール。（話題:HN Frontpage）
