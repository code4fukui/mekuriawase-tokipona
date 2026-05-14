# トキポナめくりあわせ (Toki Pona Memory Matching)

トキポナ語とその日本語訳を学ぶためのシンプルなめくりあわせ（神経衰弱）ゲームです。カードをめくって一致するペアを見つけてください。

## デモ

**ゲームはこちらで遊べます: https://github.com/code4fukui/mekuriawase-tokipona

## 特徴

- **トキポナ語の学習:** トキポナ語の単語と日本語訳のペアを見つけます。
- **ユニークなビジュアル:** カードのトキポナ語は、美しい `linja suwi` フォントで描かれています。
- **動的なレイアウト:** 16枚のカードはプレイごとにランダムに配置され、毎回新しい挑戦が楽しめます。
- **スムーズなアニメーション:** CSSの3D Transform効果により、カードが滑らかにめくれます。
- **タイム計測:** クリアまでの時間を計測し、どれだけ早くクリアできるか挑戦できます。
- **即時リトライ:** 「Retry」ボタンを押すと、すぐに新しいゲームを開始できます。

## データと依存ライブラリ

- 単語データは、トキポナ・日本語辞書CSV [tok2jpn](https://github.com/code4fukui/tok2jpn) から取得しています。
- ゲームはVanilla JavaScriptで構築されており、以下の2つのヘルパーライブラリを使用しています:
  - [CSV.js](https://js.sabae.cc/CSV.js): 辞書データのパースに使用。
  - [shuffle.js](https://js.sabae.cc/shuffle.js): カード配置のランダム化に使用。

## クレジット

本プロジェクトは、[福野泰介 (Taisuke Fukuno)](http://fukuno.jig.jp/757)氏が作成しためくりあわせゲームエンジン [mekuriawase-fukui](https://github.com/code4fukui/mekuriawase-fukui) を改変したものです。

## ライセンス

[MIT](LICENSE)
