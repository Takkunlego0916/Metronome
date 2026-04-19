# Metronome

> シンプルで使いやすい Windows 向けメトロノームアプリ
> A simple and easy-to-use metronome app for Windows.

---

## 概要 / Overview

Metronome は、リズム練習や作曲の補助に使えるデスクトップメトロノームです。
Electron をベースにしており、軽量かつ直感的に操作できます。

Metronome is a desktop metronome app designed for rhythm practice and composing.
Built with Electron, it is lightweight and easy to use.

---

## 特徴 / Features

* BPM を自由に設定可能（20〜300）
* 拍子（Beats / Bar）と分割（Subdivision）に対応
* タップテンポ機能（Tap Tempo）
* 音量調整
* ダーク / ライトテーマ対応
* 多言語対応（日本語 / English ほか）
* キーボード操作対応

  * `Space`：再生 / 停止
  * `T`：タップテンポ

---

## 動作環境 / Requirements

* Windows 10 / 11（64bit）

※ ソースから実行する場合：

* Node.js 18 以上

---

## ダウンロード / Download

👉 [Releases](https://github.com/Takkunlego0916/Metronome/releases/) から最新版をダウンロード

### 配布ファイル

* `Metronome Setup.exe`（インストーラー）
* または `Metronome.exe`（ポータブル版）

---

## インストール / Installation

### インストーラー版

1. `Metronome Setup.exe` を実行
2. 指示に従ってインストール

### ポータブル版

1. `Metronome.exe` をダウンロード
2. 任意の場所で実行

---

## 使い方 / Usage

1. アプリを起動
2. BPM を設定
3. 「再生」をクリック
4. リズムに合わせて練習

---

## セキュリティについて / Security Notice

このアプリは Electron 製のため、初回起動時に Windows Defender によって警告が表示される場合があります。

その場合：

* 「詳細情報」→「実行」を選択してください

※ 本アプリは外部通信を行いません。

---

## トラブルシューティング / Troubleshooting

### 音が鳴らない

* ボリュームが 0 になっていないか確認
* 他のアプリで音が出るか確認
* 一度再起動してから再度実行

### 起動できない

* Windows Defender にブロックされていないか確認
* ダウンロードが破損していないか再確認

---

## 開発 / Development

```bash
git clone https://github.com/Takkunlego0916/Metronome.git
cd Metronome
npm install
npm start
```

ビルド：

```bash
npm run dist
```

---

## ファイル構成 / File Structure

```
Metronome/
├─ index.html
├─ main.js
├─ metronome.js
├─ i18n.js
├─ styles.css
├─ icon.ico
├─ package.json
└─ README.md
```

---

## ライセンス / License

MIT License

---

## 作者 / Author

Takkunlego0916
