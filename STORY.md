# Day012 Story — Context Switch Cost Meter

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
- Family: switch_cost
- Mechanic: cost_estimation
- Input/Output: task_sequence -> cost_report
- Audience Promise: better_time_planning
- Publish Hook: 切替ロスを数字で可視化
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
Day012｜Context Switch Cost Meter
タスク切替の見えない損失を可視化する生産性分析ツール。（話題:HN Frontpage）
