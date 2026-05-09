# Day078 Story — Repair Ladder Builder

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day078専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: apology_tone_repair
- Mechanic: tone_ladder
- Input/Output: incident_cards -> repair_steps
- Audience Promise: 送る前に、言葉だけで済ませない形へ直せる。
- Publish Hook: 出来事と相手を入れると、行動の順番と一言がすぐ分かる。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day078｜謝り方なおし段
謝る前の行動順を決めるためのツールです。
