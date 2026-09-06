# 株式会社 A and K さま 3つのサイトのデザイン案

**構想段階のものを含むため、決定用の資料とは別URLにしてある。**

公開URL: https://easywebcraft.github.io/aandk-design-all/

| 節 | 内容 | 状態 |
| --- | --- | --- |
| 01 | 保育園サイト 3案・放課後等デイサイト 3案 | 提案済み |
| 02 | コーポレートサイト aandkcorp.com 2案 | **構想段階** |
| 03 | 料金（21,000円＋9,800円） | 21,000円は**提案済みの額** |
| 04 | ご確認いただきたいこと | |

## 料金の出どころ

**21,000円／月は `kaminote-proposal/src/proposal-kaminote.html` の03節にある
「3サイト案」の額**（既に顧客へ提案済み）。文言・箇条書きもそこから写しており、
**勝手に作った数字ではない**。あちらを変えたらこちらも合わせること。

9,800円／月は aandkcorp.com のぶん（EasyWebHP＋）で、`aandk-proposal` の
料金と同じ。**21,000円には含まれない**（3サイト案の内訳は保育園・KIDS・SMILE）。
合計 30,800円（税別）としている。

`kaminote-proposal/design.html`（かみのて2サイトの決定用）には
**コーポレートサイトを載せない**。あちらは案を決めていただくための資料で、
構想段階のものを混ぜると何を決める場か分からなくなる。

## 編集のしかた

原本は `src/design-all.html`。`build.py` が viewport・リセットCSS・OGP・noindex を
被せて `index.html` を作る。**生成物を直接編集しないこと。**

```bash
cd ~/aandk-design-all && python3 build.py
```

意匠と外枠は `kaminote-proposal/src/design-kaminote.html` から複製している。
**あちらを直しても自動では追随しない。**

## キャプチャ

`img/preview-{a,b,c}.jpg`（保育園）／`preview-day-{a,b,c}.jpg`（放課後等デイ）／
`preview-aandk-{a,b}.jpg`（コーポレート）。
**元のデザインを直したら撮り直して差し替えること**（各リポジトリからの複製）。
