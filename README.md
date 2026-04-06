# AUCを直感的に理解する — インタラクティブ解説

ROC曲線・AUC・クロス表（混同行列）・各種分類指標を、スライダーやボタンで実際に動かしながら学べるインタラクティブ教材です。

## ▶ 触ってみる

**[https://machiinagatoshi.github.io/auc-interactive/](https://machiinagatoshi.github.io/auc-interactive/)**

## 内容

1. **スコア分布とROC曲線の関係** — 分布の形（対称／非対称／二峰性／重なり大）を切り替え、しきい値を動かしてROC曲線の生まれ方を体感
2. **クロス表で理解するAUC vs 正解率** — データの偏り（均等／不均衡／極端）がAccuracyをいかに騙すかを可視化
3. **Accuracy / Recall / Precision / F1** — クロス表のどのセルを見ているかをハイライト。がん検診・スパム検出など場面プリセットつき

## 技術構成

- スタンドアロンHTML（`index.html` 1ファイルのみ）
- Chart.js（CDN読み込み）
- ダークモード自動対応（`prefers-color-scheme`）
- レスポンシブ対応

## 解説記事

note.comで背景の解説を公開しています

https://note.com/mn_no_nikki/n/na143a9911c66
