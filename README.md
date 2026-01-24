# Metronome

> シンプルで使いやすい Windows 向けメトロノームアプリ  
> A simple and easy-to-use metronome app for Windows.

---

## 概要 / Overview

Metronome は、リズム練習や作曲の補助に使えるデスクトップメトロノームです。  
Electron + Node.js で作られており、軽量で動作も高速です。

Metronome is a desktop metronome app for rhythm practice and composing.  
Built with Electron + Node.js, it is lightweight and fast.

---

## 特徴 / Features

- BPM を自由に設定可能 / Set any BPM freely
- スタート・ストップボタン付き / Start and stop easily
- 多言語対応（i18n.js） / Multi-language support
- シンプルで直感的な UI / Simple and intuitive interface
- Windows 用にビルド済み / Prebuilt for Windows

---

## 必要環境 / Requirements

- Windows 10 / 11
- Node.js 18 以上（ソースから実行する場合） / Node.js 18+ (if running from source)

---

## インストール / Installation

### 1. バイナリ（推奨）
1. [Releases](https://github.com/Takkunlego0916/Metronome/releases/) から `Metronome.exe` をダウンロード
2. 任意のフォルダに保存して実行

### 2. ソースから
```bash
git clone https://github.com/your-username/Metronome.git
cd Metronome
npm install
npm start
```

## 使い方 / Usage
1.アプリを起動
2.BPMを設定
3.再生ボタンをクリック
4.練習や作曲に合わせてリズムを刻む

## ファイル構成 / File Structure

Metronome/
├─ src/
├─ icon.ico 
├─ package.json
├─ package-lock.json
└─ README.md
